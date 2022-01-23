---
title: "Spreadsheet review I "
date:   2022-01-24
draft: true
layout: single
toc: true
show_date: true
weight:  4
description: The first of two days' training on spreadsheets. Some of it you may already know, but you may have not learned how to apply it to journalism or to follow standard newsroom practices. 
--- 

## Agenda

* Discuss Census homework
* Re-introducing the Notice of Claims data
* Demo: Pivot tables and grouping 
* Lab: Reconstructing a Census story 


## Upcoming deadlines

Sunday, 1/23
{.text-dark}

* Census assignment from boot camp

Friday, 1/28 
{.text-dark}

* From filters to pivot tables [using Notice of Claims data](https://cronkitedata.github.io/djtextbook/xl-practice-noc.html) (I hope to finish this in the lab, but it might go a little long. You have seen this data system before in our warmup life of a dataset lab.)

Sunday, 1/30
{.text-dark}

* Spreadsheet assessment . If you've been keeping up, this won't be hard. 

Monday 1/31
{.text-dark}

* Final deadline for numeracy quiz. The dean will be informed if you haven't finished it by now. 

## Preparation

### Tutorials

We went through all of this in the session in boot camp but it went by quickly and you never practiced. For some people, these will take some effort. For others, they're just review. Later in the semester I expect we'll all be closer to the same experience level, so bear with me for this week. 

*  [An Excel Refresher](https://cronkitedata.github.io/djtextbook/xl-refresher.html) . (You were assigned this in boot camp, but you might have missed it. It's the same thing on a different website.)

*  [Excel filter and sort](https://cronkitedata.github.io/djtextbook/xl-filter-sort.html) . Please watch the video and go through the tutorial, even if you're familiar with this. 

*  [Excel formulas](https://cronkitedata.github.io/djtextbook/xl-formulas.html) 

* If you don't remember how to work with fractions, percents, etc., review the [Math appendix](https://cronkitedata.github.io/djtextbook/appendix-math.html) to the course textbook

Once you've finished this, you'll be in good shape to do the homework due before class on Monday. 

### Reading 

* This story will be the basis of our lab on Monday: [Georgia’s small towns continue to shrink, new census estimates show](https://www.ajc.com/news/state--regional/georgia-small-towns-continue-shrink-new-census-estimates-show/UtBP7y33fkDXUZqABgq2BM/), Jennifer Peeples, Atlanta Journal-Constitution,  . We'll take the Census population release and try to replicate the lede and a few sentences in the piece.    

* “ [Take an Interviewing Approach to Find Stories in Data](http://mediashift.org/2014/07/take-an-interviewing-approach-to-find-stories-in-data/) ”, by Derek Willis, Mediashift, July 2014.

## Lab details

Here are the sentences from the story I picked out to replicate. We should be able to do them all using filtering, sorting and computations, but we'll have to write down the answers in the data diary.  

* "In the last year alone, more than a third of Georgia’s small towns lost population, underscoring the challenges of reviving rural areas."

* " Meanwhile, Georgia’s largest cities got even bigger last year, having no problem pulling in people from small towns and other cities. "

* " Atlanta grew more than 1 percent in the past year and is now firmly pushing its nose up against the half-million-resident benchmark and is breathing on it heavily. "

* " More than half of Georgia’s small towns — with populations under 10,000 — have lost people since 2010, compared to fewer than 1 in 6 of all towns 10,000 and up, an Atlanta Journal-Constitution analysis of the census data found. "

Data source: Georgia [Governor's Office of Budget and Planning](https://opb.georgia.gov/census-data/population-estimates) (use City and Town estimates, 2018). I [cleaned it up a little and saved a copy of the spreadsheet here](https://cronkitedata.s3.amazonaws.com/xlfiles/ga-city-town-2018-sc1.xlsx) . 

[Here is the beginning of a data diary](https://docs.google.com/document/d/1WQs0MYy8EpT9Yub7nRXM4V09Or8JJcdArQiK9jTBpBE/edit?usp=sharing) you can add to as we work through it in class.  I would like you do to it in Google Docs rather than as a separate sheet because you want to be able to move around the document easily. 

The original spreadsheet had a weird heading that suggests the estimates were from 2016, not 2018, suggesting in turn they are forecasts. I believe they just republished the format of earlier years and forgot to change the heading. I checked it against a more [recent Census release](https://www.census.gov/data/tables/time-series/demo/popest/2010s-total-cities-and-towns.html) and against the story. We can use this for our purposes. It's definitely a question to go into your data diary if this were a real situation!

I'll post a demo spreadsheet with some advanced ways of getting to these answers after the lab, but you don't have to go through it.