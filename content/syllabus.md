---
title: "Empirical Reporting"
subtitle: "(Otherwise known as MCO 510, Data Journalism, Spring 2022)"
date:   "2021-12-11"
summary: "TLDR: Sorry, you just have to read it."
classdate: "2022-01-11"
#publishDate: 
draft: true
layout: single
toc: true
--- 

M-W 10:00-11:50 Cronkite 404b (behind the elevators)
**Canvas**: https://asu.instructure.com/courses/92120/
**Slack Workspace**: https://asu-2217-jmc465-75289.slack.com/

Sarah Cohen / sarah.h.cohen@asu.edu / 202.213.6980
Office hours: Just Slack me. I’m usually around any time other than Monday through Wednesday.

Prerequisite: Basic numeracy. You will not be allowed to move forward in the class until you show that you can compute the most common numbers used in news such as fractions, percent changes and averages. An exam will be released to you as soon as you complete your Cronkite Integrity Pledge. You can use materials provided here and in Canvas as guides, but you will have to sign a statement that you didn’t just Google the answers. Your first try is due the first week; you must pass it by Jan. 30.

## Description

This is a class in data journalism focused the systematic use of public records, documents and other material in public affairs reporting. We’re calling it “empirical journalism”, but previous generations might have called it “computer-assisted reporting” or “precision journalism”. Whatever the name, the idea is the same: original reporting and analysis in the service of stories, particularly in the accountability and explanatory genres.

Analyzing records can help you confirm or disprove a tip, isolate anecdotes, and explore stories or patterns that no one has thought to mention. When you use data-driven techniques, your street reporting will become deeper and more enlightening. Better yet, the techniques you’ll learn in this class will often yield exclusive stories.

A generic square placeholder image with rounded corners in a figure.
By Chris Wormhoudt via Unsplash
By the end of the semester, you should be able to:

Identify how and when analysis of electronic records might strengthen your story, provide important insights, or suggest new lines of reporting.
Apply tools such as Excel and the R programming language for reporting in efficient, effective and ethical ways that avoid errors.
Integrate data journalism techniques with traditional reporting methods.
Write effectively with and about data, whether for text or for the ear.
Required materials and texts
All of the hardware and software required for class is available in the labs. If you choose to use your own laptop, it must be running Mac OS High Sierra (version 10.13 or newer) or Windows 10 (or newer). All Mac and Windows machines made or updated since 2017 meet these requirements. Please contact Prof. Cohen if you’re not sure if your operating system needs updating. You’ll struggle if you’re trying to do this on a tablet, and I won’t help you if you insist on trying.

A regular mouse is strongly recommended. A basic wired mouse that connects to your USB port costs about $10 on Amazon.

Books and software
You do not need to buy any books or software. This site contains or links to all of the reading, viewing, and texts you need.

The following free software will be used extensively in this class.

The Slack app. When possible, use the app rather than the version in your browser. The browser lacks some of the functions that are in the app.
A free copy of Microsoft Excel available in https://myapps.asu.edu . When you go to Office 365 there, there will be a link on the upper right to download and install Office. The online version won’t work. We’re only going to use Excel for about two weeks, so you might just want to use the ones in labs if you haven’t already downloaded it.
R and RStudio, both free community versions. We’ve tried using the cloud version in the past only to continually run into problems during your project. I don’t recommend it.
We might also use OpenRefine (Links to an external site.) for one or two classes. It’s an easy thing to install, but we’ve had mixed success getting it to work in the labs because of permissions. Don’t worry about this until it’s time.
There will be a lot of recommended books and readings in each week’s assignments.

Grading
The class uses a point system that initially adds up to 1,000 points for the semester. In the past, we’ve found that we sometimes have to drop an assignment, making the total add up to something less than 1,000. I hope we can keep on track this semester, but be prepared for it to change.

Daily work: 300 points (2/11, 3/25, 4/27)
Spreadsheet assessment: 100 points (1/30)
Data replication project: 200 points (2/20, 3/4, 3/20)
Final story memo : 250 points (3/27, 4/11, 4/17, 4/24)
Mini-projects: 150 points (1/21, 4/9, 5/2)
Daily work (300)
Doing well in this class means working slowly, methodically and consistently throughout the semester.


Matt Waite

Most weeks, you’ll have group labs to turn in along with some kind of individual homework assignment. These will not be graded individually. They’ll be marked "Complete" or "Incomplete". A complete assignment is one that is turned in on time at an acceptable level of quality – assignments free of major errors that addressed the asignment’s core instructions. I’ll promptly provide individual feedback on the assignment in Canvas.

These will be graded as a group in three assessments. You’ll provide your own evaluation of aspects of this daily work, including effort, teamwork, attention to feedback, application of the work to journalism, news judgment, and mastery of the material. I will invite you to set up a one-on-one appointment with me to discuss it and agree on the grade.

Spreadsheet assessment (100)
This assessment tests your ability to apply basic spreadsheet skills to journalism. Some of the questions will ask you how you might go about accomplishing something; some will have questions about what you might find newsworthy in a simple dataset. The only skills that are expected of you are sorting, filtering, basic math formulas, and pivot tables. In the past, people have found the journalism parts of this assessment harder than the Excel parts.

We will NOT have an R assessment, since your two projects are required to be done as R programs.

Replication project (200)
There are three separate assignments for this project, which challenges you to reproduce some sentences published in real stories using the same data used by the reporters. I’ll provide the stories and the data. Your first job is to identify paragraphs in the story that depended on the dataset that you’ve been given. The second gives you a chance to turn in a draft of your work so that I can help you. The last one is the final version.

Story memo / pitch (250)
In this project, you’ll develop a story pitch using a combination of story backgrounding and data analysis. I’ll give you a choice of three datatsets that I know will work for this assignment. You may propose your own, but it must be easy to obtain, relatively clean, and complicated or large enough that there is something for you to analyze beyond a basic statistic. Generally, the dataset will be of individual records (accidents, inspections, deaths or events), not statistical compilations. You’ll understand this better as we move along.

Althouth this is one-quarter of your grade, it’s split among four assignments over more than a month. You’ll build the memo a little at a time, so by the end, it won’t seem like a big lift. I promise.

Smaller mini-projects (150)
There are three graded assignments sprinkled througout the semester, each work 50 points. They include a close reading of a data journalism project; designing your own database for stories that don’t have data ready-made; and creating a creative explainer about anything you did during the course. These will be explained further as you move ahead.

srvyr focuses on calculating summary statistics from survey data, such as the mean, total or quantile. It allows for the use of many dplyr verbs, such as summarize, group_by, and mutate, the convenience of pipe-able functions, rlang’s style of non-standard evaluation and more consistent return types than the survey package.