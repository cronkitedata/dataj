---
title: "Story memo details"
date:   2021-12-27
draft: false
layout: single
toc: true
show_date: false
--- 

This project makes up 15 percent of your final grade. It involves analyzing a dataset that contains records that would be of interest to a story or feature.

Key deadlines:

March 27:  A three paragraph description of your proposed story memo

April 11:  Update #1 - your hypotheses and first stabs at the data

April 17  :  Update #2: Your nut graf and b-matter

April 24:   Final story memo and documentation . 

You will not much other homework or reading during this last month of the class. I expect the project to take up most of your time outside of class. Expect to spend about 20 hours on it, spread over five weeks. If you slacked off doing practice and tutorials during the R section of the course, it will take longer.  

## The proposal

In your story memo proposal, you should provide the name of a dataset you want to use as a spine for a story idea. Don't think of this as a "numbers" story. Instead, consider the range of material that the data could provide to a story including sweeping findings, leads for people or anecdotes, and places to focus your reporting.

You are welcome to propose a dataset of your own, but you should choose one of the ones I add to this page as a back-up.  I also welcome you to talk with me about a topic you'd like to explore but don't know of any readily available data that would fit this project - I might know of one.  

You are also welcome to use a dataset that you want to use for a story either in another class or that you want to do in the future. But you should show me specifically in the proposal what the dataset is, how you are going to obtain it, and have a backup in case it doesn't work for this project. The data should be easy to obtain and complex enough to provide some challenge in analysis  but not so hard that it's an unreasonable lift for the time you have. 

Your story idea does NOT have to be local or Arizona-based. It can be from any area you want, or it can be national or international. However, you should have an idea of who your target audience is before you begin. 

Your proposal should be about three paragraphs long. It should include one or two possible story lines that you think might come from the data, and at least two references to stories that have used the data or data like it in the recent past. 

To do your memo, you should familiarize yourself with what the data contains, how it has been used locally or in a publication geared at your target audience (or something like it elsewhere) so that you know whether your story idea is novel. It's ok if it's not -- localizing or updating an older story is fine. You should just know where your story idea fits in the ecosystem. Review the work we did for the "Life of a dataset" assignment early in the semester to help guide you. 

### Datasets I've pre-vetted

Here's a list of datasets that I believe meet the goals of the project and offer some interesting opportunities. I'll try to work on adding some more as we move through the semester. Please let me know if you have or know of one that is a good fit for the project. A good fit means that it's got enough complexity that you can analyze, it's easy to get or is readily available online, and it's not such a mess that you'll spend all of your time trying to understand and clean it. 

* [COVID case and death counts by county](https://github.com/nytimes/covid-19-data) from the New York Times; While it does not have population or other demographics, it does have the codes needed to match against  Census.

* [Protests in the US since  2020](https://acleddata.com/data-export-tool/) from the Armed Conflict, Location and Event Data Project. The list is done based on the carefully curated definitions the group has been using for years, making it a standardized work. It also includes an approximate latitude and longitude.  Note that you have to register with them to get access to the data. You can explore some of their international curated datasets if you prefer. 

* For News21 students: One of the datasets that you might use in your project is the Justice Department's census on police training programs, available through its [repository on ICSPR](https://www.icpsr.umich.edu/web/NACJD/studies/38250/datadocumentation) (a standard academic repository for official DOJ datasets). We'll have to determine how many people can join on this, and whether to turn it into a group project. It's pretty straightforward but might involve a lot of typing to get to something useful. Let's discuss when we get closer. 

* Business applications for [foreign labor certifications](https://www.dol.gov/agencies/eta/foreign-labor/performance) from the US Labor Department.  These are very large datasets, so be prepared to work on them at school if your computer might not handle them. You'll choose from H1B (specialty temporary workers), H2A (temporary agricultural workers), H2B (non-agricultural seasonal workers), or PERM (permanent workers). To get a good story, we'll have to piece together the list of applications from before 2020, when the borders effectively closed, with more recent ones.  PLEASE LET ME KNOW WELL BEFORE THE FIRST DEADLINE IF YOU WANT TO USE THIS DATA. I HAVE TO PUT IT TOGEGTHER FOR YOU .



## Interim deadlines
This project is done in four discrete sections, which will help you pace your work and make sure you're moving in the right direction. See the individual Canvas assignments for what is included in each. 

## The Final Product

### The pitch

The final memo should be a story pitch of approximately 1,000 words. It should include:

* A nut graf or lede that clearly relates the theme of the story and the results of your analysis so far.
* Examples of places, people, or other anecdotes derived from the data that illustrate the story
* Well-written and composed b-matter, which provides background on the story's importance and scope. 
* The results of the analysis you've done so far, and
* A detailed description of the reporting that is left to do before you can finish the story (including document requests and street reporting).

In this pitch, you will not discuss WHAT YOU DID to get to this point -- you'll actually pitch a story. 

### The documentation

We talk all semester about the need to be able to document your work and make it replicable. I expect that your work will be done almost entirely in R Markdown documents. The documentation should allow a reader to follow the data cleaning, analysis and other steps you took. 

I'll provide a template for you, and you might want to have multiple documents -- say, one for data loading , cleaning, and sourcing; and another for the actual analysis.  Generally, though, you'll have sections that include:

* Documentation about the data, including sourcing, vetting and a data dictionary of the parts you are using. 
* Loading and cleaning the data. 
* The actual analysis, including the motivating questions you're trying to answer, the code you used, and your interpretation of the results. 

You should have a lot of draft documents before you edit it for this step. In this, you'll include only the parts of your analysis that were important to your memo, not every single thing you did. Think of it as a published white paper on the data analysis you did. 

This documentation should allow anyone to follow your steps from the original dataset to the final answers. Make sure to include a link to the original dataset that you started with. If you made changes to it, you must document that as well, and submit the code/ data diary that you used to get there. I don't know how to say this any more plainly than this: Your work MUST be 100% replicable , from the original dataset that you downloaded or got a from a source, through the final analysis and memo. 

