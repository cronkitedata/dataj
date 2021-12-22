# Understanding your data

David Cullier, an expert in public records, recommends following the life cycle of a document or dataset when trying to extract it from a government agency. He wants to know where the information was born, whether it's still alive, and why it existed. 

We can take that metaphor across any form of "data". But first, it's worth remembering the dic

This reading and viewing is designed to help you recognize different types and sources of data, and to look at a few relatively short pieces of journalism that use data and empirical methods to develop the story. 

#### Data granularity 

Need to write a textbook chapter for this or record a video.  
{.text-danger}

https://eagereyes.org/basics/spreadsheet-thinking-vs-database-thinking

I will replace all of this with a chapter in the textbook that incorporates it, adding the stories at the bottom. 


#### Digital trace data

The videos suggest there is a hard line between trace data -- usually the information we get that was a byproduct of doing something else -- and custom-made data, or something like  a survey. In practice, it's not quite that firm a line and you shouldn't fret over specific definitions. Instead, focus on the concept that in some cases, we have control over what we measure, and in some cases we don't. 


Much of the data used by  journalists is "digital trace data" -- the flotsam and jetsom that is left behind when people tweet or post on Instagram, when government agencies inspect businesses, and when emails are sent between officials. This data that wasn't created for us to analyze, but it was born as a byproduct of doing something else. 

This researcher is generally talking about data we leave behind in public, in social media and through the use of our phones. But you can also think about it as public records you get through FOIA -- that is the "trace data" of government activity -- the artifacts of governing. If something is inspected, if money is spent , if a law is enforced, then it leaves behind trace data.

<iframe width="560" height="315" src="https://www.youtube.com/embed/uuSWQN7uYhk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Granular and aggregated data 

One of the hardest concepts for a lot of new data journalists is the idea of *granularity* of your data source. There are a lot of ways to think about this: individual items in a list vs. statistics, or original records vs. compilations, or granular data vs. statistics. Generally, an investigative reporter is interested in getting data that is as close as possible to the most granular information that exists, at least on computer files. Here's an example , which might give you a little intuition about why it's so important to think this way: 

Whenever someone dies in the US, a death certificate is filled out first by the attending physician and then finished up (usually) by a funeral director. Here's what one of them looks like, in its printed form. Note that there is information on the location of the person's home, their names, their parents' names, the causes of death, their ethnicity , etc. 

Let's take a trip through a death certificate and watch how it moves from the detailed -- *granular* -- form, to a form that you're used to seeing: The number of people who died of COVID-19 over the past two years. 

PUT A PICTURE OF A DEATH CERTIFICATE HERE. 

In practice, these are rarely filled out by hand anymore. Instead, they are entered into a database, where the *record layout* or *data dictionary* might look something like this (shortened for the purpose of our example)

Field name | Type | Description
---- | ---- | ------
id  |  number | The number on the top of the form
dec_lname | text | decedent's last name
dec_fname | text | decednt's first name
dob | date | date of birth
pob | text | Place of birth
home_zip | text | home zip code
death_zip | text | zip code where death occurred
primary_cod | text | ICD-11 code for the underlying cause of death (eg, COVID )
prox_cod | text | ICD-11 code for the immediate circumstances of death (eg, heart failure)
contrib1_cod | text | ICD-11 code for a contributing cause of death
dec_race | text | decedent's race 
dec_ethnicity | text | Hispanic / Latino or non-Hispanic / Latino

etc. 

Now take a look at what the government gives you from this data: 

GET A PICTURE OF A DASHBOARD

The problem is, we don't know HOW they compiled these statistics, and we can't tease them apart to get , for example, the number of people who died with COVID as a contributing, but not underlying, cause of death; or what COVID did to people that made them die (the immedieate circumstances). We can't check whether they died near home (with a zip code the same or close to their death zip code). And we can't contact their families, because we don't have the names! 

But if we started with the most granular data -- the actual dataset that contained details on each death -- we could easily calculate all of those statistics. You might even be able to do it next week if you don't know how already. 

If your source has already aggregated data like this into a set of figures that you are trying to find, there's no reason to repeat their work. But in most investigative stories, we are attempting to measure something that no one ever measured before. We are trying to aggregate data in our own way to find our own results, and we just can't do that with data that starts out missing much of the detail. 

Here are some other examples of granular data and the aggregataions you'll often see: 

* A census form ->  population by **block group** and **race**
* A crime incident report ->  the number of **violent** crimes in your **city**
* A payment to a doctor -> medical spending **government program**
* A water sample -> The number of homes with **lead** in their drinking water
* A vaccination -> vaccination rates for **measles** in a school

I've bolded the terms that have to be in the original, granular, record in order to count or sum them into those statistics.

## Your noun

That brings us to one of the most important things you must find out about any data you begin to analyze: What "noun" does each item in the dataset represent? In statistics, they might be called *observations* or *cases*.  In data science, they're usually called *records*. Either way, every row must represent the same thing -- a person, a place, a year, a water sample or a school. And you can't really do anything with it until you figure out what that is. 

In 2015, we did a story at The New York Times on deportations in the Obama administration. The government had claimed it was only removing hardened criminals from the country, but our analysis of the data suggested that many of them were for minor infractions. In writing the piece, we had to work around a problem in our data: the agency refused to provide us anything that would help us distinguish individuals from one another. All we knew was that each row represented one deportation -- not one person! Without a column, or *field* for an individual's identifier (say, name and date of birth, or some scrambled version of an Alien ID) , we had no way to even estimate how often people were deported multiple times. If you read the story, you'll see the very careful wording, except when we had reported out and spoken to people on the ground. 





