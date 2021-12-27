---
title: "Empirical Reporting"
subtitle: "(Otherwise known as MCO 510, Data Journalism, Spring 2022)"
date:   "2021-12-11"
summary: "TLDR: Sorry, you just have to read it."
#classdate: "2022-01-11"
#publishDate: 
draft: false
layout: single
toc: true
show_date: false
weight: 2
--- 


Sarah Cohen / sarah.h.cohen@asu.edu / 202.213.6980 <br>
M-W 10:00-11:50 Cronkite 404b (behind the elevators)<br>
**Canvas**: https://asu.instructure.com/courses/92120/<br>
**Slack Workspace**: https://asu-2217-jmc465-75289.slack.com/

Office hours: I can usually be available M-W except during class. Just Slack me to make sure, but stop by anytime in room 361.


<figure class="figure float-end sm-3 ps-4 " width="30%">
<img src="/dataj/img/wormhoudt.png" width="80%" class="figure-img img-fluid" ></img>
<figcaption class="figure-caption">By Chris Wormhoudt via Unsplash</figcaption>
</figure>


## Description

This is a class in data journalism focused the systematic use of public records, documents and other material in public affairs reporting. Previous generations might have called it “computer-assisted reporting” or “precision journalism”. Whatever the name, the idea is the same: original reporting and analysis in the service of stories, particularly in the accountability and explanatory genres.


Analyzing records can help you confirm or disprove a tip, isolate anecdotes, and explore stories or patterns that no one has thought to mention. When you use data-driven techniques, your street reporting will become deeper and more enlightening. Better yet, the techniques you’ll learn in this class will often yield exclusive stories.

By the end of this semester, you will be able to:

* Identify how and when analysis of electronic records might strengthen your story, provide important insights, or suggest new lines of reporting.
* Apply tools such as Excel and the R programming language for reporting in efficient, effective and ethical ways that avoid errors.
* Integrate data journalism techniques with traditional reporting methods.
* Write effectively with and about data, whether for text or for the ear.


## Required materials and texts

All of the hardware and software required for class is available in the labs. If you choose to use your own laptop, it must be running Mac OS High Sierra (version 10.13 or newer) or Windows 10 (or newer). All Mac and Windows machines made or updated since 2017 meet these requirements. Please contact me if you’re not sure if your operating system needs updating. A tablet just won't work. 

A regular mouse is strongly recommended. A basic wired mouse that connects to your USB port costs about $10 on Amazon.

### Books and software

You do not need to buy any books or software. This site contains or links to all of the reading, viewing, and texts you need. We are using a [bespoke online textbook](https://cronkitedata.github.io/djtextbook/) I made that puts together and updates a lot of handouts and tutorials I've had scattered around various Canvas sites, Google Drive docs and Github repos. It's a work in progress that will be updated throughout the semester.

The following free software will be used extensively in this class.

* The Slack app. When possible, use the app rather than the version in your browser. The browser lacks some of the functions that are in the app.
* A free copy of Microsoft Excel available in https://myapps.asu.edu . When you go to Office 365 there, there will be a link on the upper right to download and install Office. The online version won’t work. We’re only going to use Excel for about two weeks, so you might just want to use the ones in labs if you haven’t already downloaded it.
* R and RStudio, both free community versions. We’ve tried using the cloud version in the past only to continually run into problems during your project. I don’t recommend it.

We'll discuss any other software. We may use Github as a repository for some of the assignments, and we may use OpenRefine for data cleaning. Both are free. 

#### Recommended 

[The Art of Access: Strategies for Acquiring Public Records](https://www.amazon.com/Art-Access-Strategies-Acquiring-Records/dp/1506380700/ref=pd_sbs_14_t_0/141-5195764-7429116), David Cullier and Charles N. Davis, 2nd edition (2018).   This is an invaluable guide for this most important part of your reporting tradecraft, but it's quite expensive. 

[Investigative Reporters' Handbook: A Guide to Documents, Databases, and Techniques](https://store.macmillanlearning.com/us/product/Investigative-Reporters-Handbook/p/1319102840?_ga=2.33227454.1887889074.1629301752-1807901874.1626798218), 6th Edition , by Brant Houston and Mark Horvit, 2021. Available for rent or purchase from MacMillan Learning. I believe this will be a required text elsewhere in your program - if so, I'll make use of it. If not, it's a great guidebook. Be sure not to purchase an earlier edition - the 6th is a major rewrite.

## Grading

The class uses a point system that initially adds up to 1,000 points for the semester.  

* Daily work: 300 points  
* Spreadsheet assessment: 100 points  
* Data replication project: 200 points  
* Final story memo : 250 points  
* Mini-projects: 150 points 

**Numeracy quiz**: You will must show that you can compute the most common numbers used in news such as fractions, percent changes and averages. Materials are provided to you to remind you of these most essential math skills.
{.alert .alert-info .opacity-75}

### Daily work (300)


Doing well in this class means working slowly, methodically and consistently throughout the semester.

<figure class="figure  sm-10 ps-4 " width="60%" alt="Matt Waite quote: Not due today, not doing it today">
<img src="/dataj/img/mwtweet-edited.png" width="100%" class="figure-img img-fluid" ></img>
</figure>

Most weeks, you’ll have group labs to turn in along with some kind of individual homework assignment. These will not be graded individually. They’ll be marked "Complete" or "Incomplete". A complete assignment is one that is turned in on time at an acceptable level of quality – assignments free of major errors that addressed the asignment’s core instructions. I’ll promptly provide individual feedback on the assignment in Canvas.

Instead, I'll grade these as a group three times during the semester. You’ll provide a self-assessment addressing aspects of this daily work including mastery of the material, application of it to your journalism, effort, teamwork, and attention to feedback. I will invite you to set up a one-on-one appointment with me to discuss it and agree on the grade.

### Spreadsheet assessment (100)

This assessment tests your ability to apply basic spreadsheet skills to journalism. Some of the questions will ask you how you might go about accomplishing something; some will have questions about what how you might find news in a simple dataset. The only skills that are expected of you are sorting, filtering, basic math formulas, and pivot tables. In the past, people have found the journalism parts of this assessment harder than the Excel parts.

### [Replication project](/dataj/replication/) (200)

There are three separate assignments for this project, which challenges you to reproduce some sentences published in real stories using the same data used by the reporters. I’ll provide the stories and the data. Your first job is to identify paragraphs in the story that depended on the dataset that you’ve been given. The second gives you a chance to turn in a draft of your work so that I can help you. The last one is the final version.


<div class=" alert float-end w-50 m-3 p-3 alert-info opacity-75">

This course follows ASU's grading policies:
{.fw-bold}

* "A" is reserved for "excellent" or "outstanding" work, which goes beyond the requirements in quality, depth, effort, or presentation.<br>
* "B" means "good" -- really! That means it's on time, accurate, written or presented in a professional way, and answers the requirements of the assignment. <br>
* "C" is considered "Acceptable" work, in that it has met some, but not all, of the requirements.

</div>

### [Story memo](/dataj/memo/) / pitch (250)

In this project, you’ll develop a story pitch using a combination of story backgrounding and data analysis. I’ll give you a choice of three datatsets that I know will work for this assignment. You may propose your own, but it must be easy to obtain, relatively clean, and complicated or large enough that there is something for you to analyze beyond a basic statistic. Generally, the dataset will be of individual records (accidents, inspections, deaths or events), not statistical compilations. You’ll understand this better as we move along.

Althouth this is one-quarter of your grade, it’s split among four assignments over more than a month. You’ll build the memo a little at a time, so by the end, it won’t seem like a big lift. I promise.

### Smaller mini-projects (150)

There are three graded assignments sprinkled througout the semester, each work 50 points. They include a close reading of a data journalism project; designing your own database for stories that don’t have data ready-made; and creating a creative explainer about anything you did during the course. These will be explained further as you move ahead.

## Course policies

 <blockquote class="blockquote">
    <p>Showing up is 80 percent of life.</p>
    <span> <a href="https://quoteinvestigator.com/2013/06/10/showing-up/" class="text-decoration-none link-secondary">Woody Allen </a></span>
  </blockquote> 

This is an immersioin, in-person class and is not offered via Zoom or ASU Sync.  The minimal requirement is to arrive on time, prepared, and ready to work. Please refrain from eating, napping, using social media, shopping, or working on something else. Be polite to your classmates and any guests by paying attention and respecting their time.

### Attendance and deadlines

There are no excused absences  in this course, except for true medical or other emergencies or religious observances.  You might decide it’s more important to schedule a job interview, attend a family event, or  interview a source than to attend class or complete your work. You might decide to skip class in order to accommodate another class -- something your professors are not supposed to have you do. If I were you, I might decide the same thing, but these are choices that reflect your priorities. They’re not emergencies, nor are they excused absences or deadlines. 

As in all journalism work, you are expected to meet deadlines.  Assignments submitted even one minute past the deadline will not be accepted and will receive zero credit. 

That said, **give yourself a break**. You may miss one class and get an extension on one routine (ungraded) assignment without penalty. Notify me on Slack when you plan to take it.  

In the event of extreme circumstances, such as a natural disaster, a death in the family or severe illness, notify me right away. I am required to notify the Dean of Students when this happens, who will then coordinate the support services and accommodations needed across the university.


### Accuracy

If you pursue reporting with data-driven techniques, you’ll often create original information that no one else can confirm. In fact, your sources are often happy to explain a result you present to them, even if it’s entirely wrong. This puts an even bigger burden on you to understand your sources, to question your assumptions and find holes in your work. If an answer seems too newsworthy, walk through everything you’ve done step by step. Seek out errors; ask experts or colleagues to challenge your results. We’ll spend a lot of time on practices that will help protect you from errors but your own skepticism (and sometimes even fear) is the best defense.

I don’t expect your work to be polished and exact. However, work that shows a fundamental misunderstanding of the source, contains a severe miscalculation or misinterpretation, or ignores clear warning signs will receive an E. This is the equivalent of having to retract an entire story because it was based on an obvious falsehood.

<div class="container ltblue-box">

Having trouble? 
{.fs-2}

<figure class="figure float-end sm-6 ps-4 " width="60%">
<img src="/dataj/img/moller.png" width="100%" class="figure-img img-fluid" ></img>
<figcaption class="figure-caption">By Fabian Moller via Unsplash</figcaption>
</figure>


Learning data skills requires a lot of trial and error -- a LOT of error. It's frustrating and maddening at times and you won't be alone. But there are some strategies that you can use to help get you past roadblocks.

* Slow down! Unlike the rest of journalism, going faster doesn't help. Separate the problem into pieces and solve it one step at a time. 
* If you've been working on something for more than 20 minutes **without making any progress**, don't waste more time on it. If you're making just a little progress, keep going. But take a break and come back to it if you're stuck. Get help if you're really stuck.
* Remember the goal: We're not trying to become social scientists, computer programmers or data analysts. We're journalists. Simplify your questions, focusing on newsworthiness rather than academic research.
* Practice on something you're working on outside of school or for another class.

</div>

### Collaborations

All work submitted under your name must be your work and your work alone. When you are assigned work in teams, contributors should be credited when an individual was primarily responsible for a portion of the work. For example, if one student takes the lead on analyzing data and another on writing the results, you should give credit where it is due.

### Extra Credit

Simple. There is none. Why? This course is made up of a lot of little pieces. They can’t be replaced by attending a lecture.

<figure class="figure"  >
<img src="/dataj/img/brodeur.png" height="90%" class="figure-img img-fluid" ></img>
<figcaption class="figure-caption">via Unsplash</figcaption>
</figure>

## FAQ

**Q: I don’t have any experience. What do I need to succeed?**

For undergraduate and 3+1 graduate students, I expect that you have had exposure to Freedom of Information concepts; the one-credit introduction to programming course and the numeracy exam you had to pass in JMC 201. Beyond that, I expect a minimal familiarity with spreadsheets in general, and Excel in particular. 

**Q: This looks like a lot of work. How long do I have to spend on it every week?**

I expect that this course will follow the typical ASU time commitment -- approximately 9 total hours per week. That suggests that, on average, you should expect to spend about 5 or 6 hours per week outside of class on preparation, homework and projects. The time commitment is a little front-loaded as we race to get you the skills you need to apply them later in the semester. But please let me know if you are spending considerably more time on it -- that's not the intention. 

**Q: What is the Slack Channel**

Slack is a messaging and teamwork app that has become the de facto standard in newsrooms, including Cronkite News and News 21. You should set up alerts for key channels to be sure you’ll get class announcements. There is an assignment for the first day with guidelines to set it up.

**Q: How should I communicate with you?**

Slack or in person is best. All assignments MUST be turned in via Canvas assignments. Do NOT email assignments. There are too many moving parts in this course, and I can’t guarantee I’ll keep track of anything submitted outside Canvas and Slack.

**Q: How will I know how I’m doing?**

Pay attention to the feedback on  your routine homework and labs. I'll give you a sense of whether your work is excellent, good or acceptable. If it's not where you'd like it, let's talk about how to improve. 

**Q: How do I ask good questions?**

In technical work, asking a good question is an art. Try to:

* Describe what you are trying to do – what does success look like? What question are you trying to answer? 
* Provide a snippet of the code or the Excel formula that you’re trying
* Take a screen shot or quote the error message if there is one

**Q: I already know how to code and analyze data. Why do I have to take this class?**

Even if you know how to code, I presume you are at Cronkite because you want to apply all of your skills to a journalism career. You probably knew how to use a phone or take a picture before you came to j-school, but you may not have used them the way you do now. That said, talk with me if you’re concerned that you won’t be challenged enough. We’ll find ways to make the time productive and take you to the next level in data reporting.

*Additional Cronkite policies, including the Academic Integrity Policy, are included on the Canvas page for this class. These policies apply to all students in all classes.*

