---
title: "Replication project details "
date:   2021-12-27
draft: true
layout: single
toc: true
show_date: false
--- 

The aim of this project is to identify and replicate the major findings from a story or series. It will be completed in three parts, which altogether accounts for 15 percent of your final grade.

## How it works

You'll study the story and identify the key facts that derived from the primary dataset used. Then, over the course of a couple of weeks, you'll try to replicate those findings using the R skills you will be learning in class. 

We'll spend some time in class on labs so you can get help when you're stuck. I'll provide some templates for you to follow, but it's up to you to make a document that is readable,  understandable and produces the answers in context.

**Part 1 (50 points)**: Write approximate 500 words identifying the three most important paragraphs from the story that resulted directly from the data analysis, and explain why you chose each of them. In addition, note any characters, locations or other details that you suspect came from the data.

Once this part is done, I'll pick the findings that I want you to reproduce.

**Part 2 (50 points)**: Turn in a draft R Markdown document that starts trying to recreate the data points we agree on from your story. I don't expect this to be finished, but it should at a minimum have a) loaded the data into R, and b) attempted to answer at least one of the findings that you are trying to reproduce. You shouldn't try them in order. Instead, look for things that you already know how to do.

The more of the questions you attempt, the more feedback I can give you on your work.

**Part 3 (100 points)** Turn in a final R Markdown document with your attempts at replicating each of the findings. It should contain the code used to load the data, do any cleaning or matching to other datasets, and be self-documenting. It should be well-structured: Use headings to introduce new parts of the data, and write explanations of what you are doing in the analysis. It should be free of factual and grammatical errors, and I should be able to run it without error.

## Story / dataset choices

There will be instances in which the sentence in the story will not be exactly the same as what you calculate. You may also disagree with the way it's characterized. That's ok. Sometimes, data is updated after the original story. Don't assume it's an error on the part of the reporteres -- things change.

We will settle on three of these in class, but here are the ones I'm considering for this year. If you've seen a story that you'd like to try, please let me know -- we can always ask the reporter for the data or methodology if it's a good fit for the project. 


### Unsolved homicides in Baltimore (Washington Post)
{.text-blue}


Story: [As police struggle to solve homicides, Baltimore residents see an ‘open season for killing](https://www.washingtonpost.com/investigations/as-police-struggle-to-solve-homicides-baltimore-residents-see-an-open-season-for-killing/2018/12/26/7ee561e4-fb24-11e8-8c9a-860ce2a8148f_story.html) <br>
Github [repository with data](https://github.com/washingtonpost/data-homicides) <br>
Difficulty: Medium


### Invasive Strip Searches in New York (Propublica)
{.text-blue}

Story: [Over a Dozen Black and Latino Men Accused a Cop of Humiliating, Invasive Strip Searches. The NYPD Kept Promoting Him](https://www.propublica.org/article/over-a-dozen-black-and-latino-men-accused-a-cop-of-humiliating-invasive-strip-searches-the-nypd-kept-promoting-him) <br>
[Data download](https://www.propublica.org/datastore/dataset/civilian-complaints-against-new-york-city-police-officers) (you'll have to agree to the Terms of Service) from ProPublica's data store <br>
[Data documentation](https://projects.propublica.org/nypd-ccrb/#about) from ProPublica<br>
Difficulty: Medium

 
### LA is slammed with record payouts (Los Angeles Times)
{.text-blue}

Story: "[L.A. is slammed with record costs for legal payouts.](http://www.latimes.com/local/lanow/la-me-ln-city-payouts-20180627-story.html)". <br>
[Data](https://github.com/datadesk/la-settlements-analysis) Look at "input" data for list and categories <br>
Difficulty: Easy


### Disasters (Washington Post)
{.text-blue}

Story: ["Nearly 1 in 3 Americans experienced a weather disaster this summer"](https://www.washingtonpost.com/climate-environment/2021/09/04/climate-disaster-hurricane-ida/) <br>
Data: The Post isn't making this data publicly available, but I will create something that will get you close. You may not be able to replicate it exactly, but it will be very close.<br>
Difficulty: I don't know!

### Medicare (Wall Street Journal)
{.text-blue}


Story: [Taxpayers Face Big medicare Tab for Unusual Doctor Billings](https://www.wsj.com/articles/taxpayers-face-big-medicare-tab-for-unusual-doctor-billings-1402364264), John Carreyou, Christopher S. Stewart and Rob Barry, June 2014 (Pulitzer Prize winner) <br>
Data: I will prepare the data for you. It may not end up being exactly what the reporters found, but it will be close. It will be derived from the [2014 Public Use file](https://data.cms.gov/provider-summary-by-type-of-service/medicare-physician-other-practitioners/medicare-physician-other-practitioners-by-provider-and-service)  <br>
[Documentation](https://data.cms.gov/resources/medicare-physician-other-practitioners-by-provider-and-service-data-dictionary): Data dictionary from Centers for Medicare and Medicaid <br>
Diffulty: Hard