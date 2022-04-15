---
title: "Mapping with QGIS"
date:   2022-04-10
draft: true
layout: single
toc: true
show_date: false
--- 

This document will serve as an outline for the items that we are going to cover in the QGIS tutorial. Here, we'll use information from the PPP data we dealt with all year to convert the individual loans into summaries by Census tract -- even though there are no Census tracts included in the data. 

## Geographic data

Geographic data comes in several forms: 

* **Points** are individual dots on a map. They are located using geographic coordinates, usually expressed in decimal degrees. The coordinates for the Cronkite School are xxx latitude and xxx longitude. (Western hemisphere longitudes are always negative. Northern hemisphere latitudes are always positive.) You need about four decimal places to get an approximately good location -- more if you want the exact location of a building. 

* **Lines** are combinations of points that turn into a continous segment -- curved or straight. We don't use lines that much in journalism, except in two specific cases: roads and rivers. I'm not very good at using them or at flow analysis, so we'll skip that! 

* **Polygons** are combinations of lines that form a closed shape. They can sometimes have multiple parts, like the shape of Michigan, which has the lower and upper peninsulas. We use polygons a lot for counties, states, lakes, Census tracts, and even zip codes. 

### Point data

Addresses can be turned into points  using a process called "geocoding". This is done services that have big, huge databases of every possible address from the Postal service, Census bureau and local property data.  For example, almost every city has some type of Martin Luther King street, boulevard, avenue or road. These are sometimes put in the wrong city, even if you specify a city or zip code.  A "street" can be different than an "avenue" with the same name. And directionals can be more important than the street name itself. In DC, North and South Capitol streets are completely different but geocoders will treat it as a minor difference. There's also a street called "Nannie Helen Borroughs Ave. NE" that was changed in the 1990s, and its old name is still in some of the records. It's common to catch about 95 percent of addresses quite well. A few mistakes are fine, but you should always check to see if there is a consistent error when your geocoding fails or when you find a mistake. Large cities sometimes have publicly accessible free geocoders that take into account local issues, such as the odd two-number addresses in Queens, NY.  

When you type an address into Google Maps, you're using its geocoding service to put it on a map. But Google ($) charges a lot for access to it for your own analysis rather than its maps. Geocodio and Open Street Maps are two alternatives that have good geocoding. 

Whenever you have an option to obtain geographic coordinates in a CSV file, take them. They can be easily converted to maps. This is the only kind of geographic data that is easy to distribute in a simple data file .  The coordinates will likely be much more accurate than geocoding. For example, when a police car goes on a call, they hit a button in the car when they reach their destination, which records the geographic coordinates. But when they give you information, they'll probably give a nearby address or intersection, even when it's in the middle of an alley or on a street with only one building.

### Satellite (and other raster) data

Satellite data are pictures that have geographic positioning attached to them. This is called "raster" data, because it's not a polygon or  point or line -- it's literally a bunch of pixels with different colors in them. We won't be getting into it, but it's way cool. 

## Geographic data files

Because of its complexity, geographic data is distributed in a spatially-aware type of data set. These are usually *shapefiles*, *geojson files*, *geodatabases* or *KML* files. They each work a little differently, but shapefiles are the most common. A shapefile is really a zipped file of several types, each with the same name and a different extension. You need at least three : shapename.shp, shapename.dbf and shapename.prj. (the prj one might be missing. We'll get back to that later.) Most programs are smart enough to use the zipped version without unzipping it. 

### Practical workflow

Shapefiles are often re-used for a lot of projects. I keep one folder on my computer with common GIS files. When we get to QGIS, you'll see that it's really a pointer to a location on your hard drive. The downside is that if you move from one computer to another, your project will break. 

### Projection information

We'll get to projections later, but the fundamental idea is that every geographic element has to have some translation between a globe and a flat piece of paper. Every map is a lie -- only direction, distance or shape can be right at any given time. Projections are used to define which of those elements you care about. States usually have a standard for all agencies so that you know what projection they have been saved in. Census data is always "unprojected", using a measurement system called NAD 1983, which stands for the 1983 version of North American Datum. Most international and environmental data use a global system instead, called WGS 84. But you have to find out from the creator of the map what the projection and "datum" is before you can do anything with it.

The more local you get, the less this matters (until it's time to combine it with another geographic file). A square block doesn't have any real curviture of the earth to deal with, nor do many cities. But as you start getting to larger and larger areas, the distortion of the globe becomes more and more pronounced. 


### How to see background

You're used to seeing Google maps with the terrain and roads. When you open something in QGIS, there isn't any of that! You need to add something called a "base map". These are images that get scaled with the zoom level. There are several free sources of them - here's a list: https://atcoordinates.info/2020/12/17/adding-basemaps-to-qgis-with-web-mapping-services/



## Adding points to a map

We'll walk through opening up QGIS and getting used to some of the jargon. There are lots of great tutorials out there for this, but this just gets you started, and I hope gets you over the usual sticking points. 




### Where to get map data

Most states, counties and cities have GIS departments that have open data. In Arizona, there is something called AZGEO hub, which is a clearinghouse for GIS data in the state. Most state agencies and many local governments use the hub as a way to distribute and share their geographic data. You have to sign up for a free account to access some of it. 

At the federal level, the USGS (US Geographical Service) is a good start. But several departments have very active GIS applications, including the USDA and the Weather Service. 

When you're looking for it, just type "shapefile" or "GIS" in front of your Google search. 

You also probably won't be able to make your own data for anything other than points. That's why GIS systems are so expensive. 


### Some data to play with

The company Geocodio created latitude and longitude and accuracy scores for all of the PPP data as of June 2021, and made them available to reporters. In fact, they actually attached all of the Census data to those loans, but we're just going to use the points they created from the loans as our sample data so you can see how to do it yourself. 

In addition, we'll only take a small portion of our PPP data -- those in the main area of Phoenix proper. The reason is that geographic data with too many points will bring your computer to a screeching halt. 

According to Geocodio's documentation, all data is geocoded using EPSG:4326, othewise known as "WGS 84". That's what's important.
I've saved it as a [csv that you can download here](). 

## Starting QGIS

QGIS was created as an open source project when ArcMaps became too expensive for most casual users like us. It's designed to use and analyze map data, not to create or distribute it to others. This simplifies things a lot! 

But it's not intuitive. 

## Tutorials and 