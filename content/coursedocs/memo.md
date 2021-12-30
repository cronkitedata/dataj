---
title: "Story memo details"
date:   2021-12-27
draft: true
layout: single
toc: true
show_date: false
--- 

This project makes up 15 percent of your final grade. It involves analyzing a dataset that contains records that would be of interest to a story or feature.

Key deadlines:

March 27:  A three paragraph description of your proposed story memo
April 11:  Update #1 - your hypotheses and first stabs at the data
April 17  :  Update #2: Your nut graf and b-matter
April 24:   Final story memo and documentation . Yes, this is the day before Thanksgiving. You are welcome to submit it earlier, but this is the drop-dead date. 
My hope is that much of the work on this project can be done in labs during class time.  

## The proposal

In your story memo proposal, you should provide the name of a dataset you want to use as a spine for a story idea. This doesn't have to be a "numbers" story, and it can take many forms. You might use a dataset to: 

* Find a place to center your reporting on a topic
* Create a visual story using charts and narrative form. 
* Propose the nut graf of an investigative story based on analysis you do from the data. 

You are welcome to propose a dataset of your own, but you should choose one of the ones I add to this page as a back-up.  I also welcome you to talk with me about a topic you'd like to explore but don't know of any readily available data that would fit this project - I might know of one. For example, Census data can be used for a wealth of story ideas; there are readily available datasets on companies that have received federal dollars for pandemic relief and disasters, and those that have applied for visas for their workers under various special programs like agriculture or seasonal workers.   

Your story idea does NOT have to be local or Arizona-based. It can be from any area you want, or it can be national or international. However, you should have an idea of who your target audience is before you begin. 

Your proposal should be about three paragraphs long. It should include one or two possible story lines that you think might come from the data, and at least two references to stories that have used the data or data like it in the recent past. 

To do your memo, you should familiarize yourself with what the data contains, how it has been used locally (or something like it elsewhere) so that you know whether your story idea is novel. It's ok if it's not -- localizing or updating an older story is fine. You should just know where your story idea fits in the ecosystem. Review the work we did for the "Life of a dataset" assignment to help guide you. 

## Datasets I've pre-vetted

Here's a preliminary set of datasets that I believe meet the goals of the project and offer some interesting opportunities. I'll try to work on adding some more as we move through the semester. Please let me know if you have or know of one that is a good fit for the project. A good fit means that it's got enough complexity that you can analyze, it's easy to get or is readily available online, and it's not such a mess that you'll spend all of your time trying to understand and clean it. 

* COVID case and death counts by county from the New York Times; While it does not have population or other demographics, it does have the codes needed to match against  Census.

* Protests in the US since May 2020 from the Armed Conflict, Location and Event Data Project. The list is done based on the carefully curated definitions the group has been using for years, making it a standardized work. It also includes an approximate latitude and longitude.  Note that you have to register with them to get access to the data. You can explore some of their international curated datasets if you prefer. 

* Loans from the Paycheck Protection Program, or PPP from the Small Business Administration. This Senate committee overview is a good description of the program.  If you choose this, I ask that you select a region or industry or some other subset of the data so that you don't need to work with all 2 million rows of this dataset.  Review the [record layout](https://data.sba.gov/dataset/ppp-foia) before you make a suggestion, and 


## Interim deadlines
This project is done in four discrete sections, which will help you pace your work and make sure you're moving in the right direction. See the individual Canvas assignments for what is included in each. 

## The Final Product

### The pitch

The final memo should be a story pitch of approximately 1,000 words. It should include:

* A nut graf or lede that clearly relates the theme of the story and the results of your analysis so far.
* Examples of places, people, or other anecdotes derived from the data that illustrate the story
* Well-written and composed b-matter, which provides background on the story's importance and scope. 
* A description of the analysis and research you’ve done so far, and
* A detailed description of the reporting that is left to do before you can finish the story (including document requests and street reporting).

You'll have a lot of materials provided that help you craft a great pitch as we move along. 

In this, you will not discuss WHAT YOU DID to get to this point -- you'll actually pitch a story. 

## The documentation

We talk all semester about the need to be able to document your work and make it replicable. I expect that your work will be done almost entirely in R Markdown documents. The documentation should allow a reader to follow the data cleaning, analysis and other steps you took. 

I'll provide a template for you, and you might want to have multiple documents -- say, one for data loading , cleaning, and sourcing; and another for the actual analysis.  Generally, though, you'll have sections that include:

* Documentation about the data, including sourcing, vetting and a data dictionary of the parts you are using. 
* Loading and cleaning the data. 
* The actual analysis, including the motivating questions you're trying to answer, the code you used, and your interpretation of the results. 

You should have a lot of draft documents before you edit it for this step. In this, you'll include only the parts of your analysis that were important to your memo, not every single thing you did. Think of it as a published white paper on the data analysis you did. 

This documentation should allow anyone to follow your steps from the original dataset to the final answers. Make sure to include a link to the original dataset that you started with. If you made changes to it, you must document that as well, and submit the code/ data diary that you used to get there. I don't know how to say this any more plainly than this: Your work MUST be 100% replicable , from the original dataset that you downloaded or got a from a source, through the final analysis and memo. 