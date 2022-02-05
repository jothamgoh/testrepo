---
title: "Chapter 5b: Learning data analysis part 2"
last_modified_at: 2020-12-06 15:31:19
categories:
  - Ebook
tags:
  - Data Analyst
---
We covered Pandas, EDA, and Python visualisations in the previous section. We then reinforced the concepts through practice. This gives us a firm base to layer more concepts on. 

What about extracting data from databases?

Or analysing how often past events occur? Or better yet, predicting the likelihood of future events?

How about building useful dashboards for your team? 

SQL, statistics, and visualisation software will help you accomplish the above tasks. Let's start.  

### SQL vs Pandas

Structured Query Language, or SQL is used to communicate with databases. It's purpose is niche, but it's necessary. In fact, SQL will likely be your bread and butter. The tool you'll use the most.  

Python, like most other programming languages, is like baking bread. First, assemble the ingredients then dissolve yeast and start kneading the dough. Wait for the dough to rise, punch it, and then put it in the oven. 

It's a series of steps. It's procedural. 

SQL is not like that. It's a non-procedural programming language. In SQL, you just declare what you want. You declare what tables to take data from and what columns you want to see. Wait, and voilà. The database gives you the data that you want. 

Although Python and SQL are different, you've already encountered many SQL concepts. Where? When we learnt and practised Pandas. 

You can join two different data sources in Pandas. So can you with SQL.

You filtered records based on conditions with Pandas. So can you with SQL.

You summed numerical data with Pandas. 

So can you with SQL.

Although SQL and Pandas can do similar things, it's not a question to either use SQL or Pandas. Both have very different use cases. It depends on where you are in your process of obtaining and analysing your data. 

SQL is indispensable to get raw data from databases. It's the de facto way, the standard. It's the foundation for almost all structured data you'll ever find. I started out with Python/Pandas, but I learned really quickly that I had to pick up SQL. No SQL, no raw data.

But when it comes to exploring, munging and transforming data, SQL can't rival the flexbility of Pandas or even Excel. I dare anyone who claims the contrary with the words "pivot table".

There are exceptions, of course. SQL is much more efficient when exploring large datasets. 

I used to pull browsing data for millions of customers on a Ecommerce site. Every product viewed and every button clicked was tracked. A month of data was more than 30 gigabytes. My desktop struggled to load the data in Pandas as they wasn't enough RAM. It hanged. I had resort to using Dask - a Python library that loaded data in smaller chunks so the entire dataset could be loaded in memory. 

It is possible to do it in Python? Yes. 

But is it practical? No. It's slow.

With mammoth datasets, it's more efficient to use SQL to "pivot" the data. Know the views you want first, and use SQL to group the data. 

The overarching principle: ****use SQL to provide clean, comprehensive raw data, as close as possible to the format needed for further analysis. If further analysis can't practically be done in Python, you'll have to use SQL instead. 

### Learn SQL

The language SQL is simple. There are only a few keywords, and each one does one task. But SQL queries can be long and complicated depending on how you manipulate data. I once wrote a 1000 plus line SQL query with many sub tables. 

I'd wager you'll be able to write basic SQL queries with 4 hours of practice. That's half a day's work. But to be an SQL expert, you'll have to practice. A lot of practice, on many different problems.  

For the skills we previously learnt, we first watched a quick video course and then started practising. The video course helps you level up from:  

level 0: not knowing what you don't know, to 

level 1: knowing what you don't know. 

For SQL, a video course is strictly optional. The concepts are simple enough, and it's a "learn through practice" type of language. There are many SQL tutorial practice SQL websites out there. My favourite one for complete beginners is [sqlzoo.net](https://sqlzoo.net/). Start practising SQL within 2 minutes of landing on the site. sqlzoo teaches SQL in stages, starting from the very beginning. 

If you choose a video course, this [free Udacity SQL course](https://www.udacity.com/course/sql-for-data-analysis--ud198) is engaging and covers all the SQL concepts and keywords you'll need to start. Joins, aggregations, subqueries, window functions. If that sounds foreign, don't worry because the course brings you from an absolute beginner to intermediate. Focus on understanding concepts during the course. You can always google keywords if you forget. After the course, don't forget to practice. Here are some other free SQL practice resources: 

Leetcode 

### Learn Statistics

Why only learn statistics now? Because you already did exercises on Kaggle. Learning it now helps a boring textbook come alive as you can imagine what statistics is used for. 

I love statistics. It's practical, meaning you can use it in real life to give you an edge. It's a subtle superpower. Most of the decisions we make are inferred, and statistics is your best protection against fooling yourself in a very uncertain world. 

Want to see if you should buy a lottery ticket for the 10 million dollar draw? Use statistics to calculate the expected value of each lottery ticket. In 2005, a group of MIT students used statistics to [game the Massachusetts state lottery and won millions](https://www.theatlantic.com/business/archive/2016/02/how-mit-students-gamed-the-lottery/470349/).  

Or do you have a website and need to decide if customers react better to your new landing page? Use statistics to be reasonably confident whether to keep the website change or not. 

Or learn statistical techniques related to machine learning. Popular algorithms such as linear and logistics regression. 

So far, we've used informal resources to acquire many skills. Websites like [sqlzoo.net](http://sqlzoo.net), Udemy courses to learn Python and Pandas, and Kaggle for practice. We'll change it up and take a formal approach instead to learn statistics. 

Why? I did a few non-formal statistics courses. The courses either diluted the topic and even gave incorrect explanations at times. This does more harm than good. 

The best statistics resource I've come across is a unexcitingly named textbook called "OpenIntro Statistics". It's free, but you can opt to pay for it. [Find it online here](https://leanpub.com/openintro-statistics). This book is written by a professor at Duke University, and it's used in an excellent online course on Coursera called ["Introduction to Probability and Data with R"](https://www.coursera.org/learn/probability-intro).  This course is also free, and it's really good if you prefer learning using video. The only caveat is that it's done in R. 

The OpenIntro Statistics book is engaging, with many real life practical examples. There's nothing worse than a theoretical explanation in math. Conversely, seeing math applied is akin to seeing how superpowers are used in real life. 

The book covers probability distributions, hypothesis testing, linear and logistic regression, and more. This may sound dull and technical. But these concepts come alive in this book. You'll come out with many more ideas on how you can apply statistics in your own life.

The exercises in the book is the best part. I've never had math concepts stick unless I practised a few problems. Each exercise has a practical context. From analysing spaces launches in the US to interpreting SAT scores. 

There are exercise solutions are the end of the book to validate your answers. The solutions have good explanations. There are also data sets which as used in the book that you can download and practice.  

Finish this book and the exercises, and you'll be literate in statistics and probability. 

## Data Visualisation Software

Companies spend A LOT on visualisation software. Such software hold the promise of a data driven culture. Empower employees with data and make smart decisions, they say. 

Tableau, Qlikview, and Looker are the most commonly used software. But there are literally hundreds others, and it's often the data analyst's task to build dashboards. 

So which one do you learn to make yourself more employable? 

It's a clear decision if you're upskilling in your current company. What if you're looking for a new job, or looking to transition from something unrelated to a data analyst role? 

The good news is that it doesn't matter which tool you learn. In fact, learning such software is optional. You already have the building blocks needed to use such software. Most visualisation software work similarly. First, build a data pipeline to bring data from your database to the software. Then, use the software to create tables, views, and graphs. 

You've already learnt SQL which helps pull data from databases. 

You've learnt Python to help with ETL data pipelines.

You've learnt what visualisations to plot based on on the type of data. 

That's really all the building blocks you need to build dashboards. In fact, the software is designed to make your job easy. Tableau's strength for example is being able to pull data not just from SQL databases but also from almost any other data source you can think of. From Google Sheets, to Dropbox. It's then really easy to make fancy plots in Tableau. In fact, it's mostly is choosing the best options from a fixed list. 

There still will be a learning curve of course. Each software will have it's own quirks. But learn visualisation software on the job. It saves you time and effort lest you learn a specific software that your future employer doesn't use. Employers also won't have the expectation of you to be an expert in such software. Think of knowing the exact software as a good to know but far from being a deal breaker.

In practice, the most important thing is to build dashboards that are used. This means understanding what the business wants by asking the right questions. Then evaluate what data will help solve the problem. Dashboards with fancy graphs with "good to know, but not directly actionable" data will be quickly ignored. 

## It's a wrap, but there's more

Congrats for making it this far! We've learnt how to learn, as well as covered resources and mindsets to be a successful data analyst. We've talked about Python, Pandas. Cleaning, EDA and visualisation. SQL, statistics, and data visualization software. 

But what's the use of learning all these if your interviewers can't see your value? I'll break down interview strategy in the next sections. The goal: convert resumes to job offers. Luck plays a part in every job application. The critical question is not, will you get lucky? But what will you do with the luck that you get? Let's maximize your return on luck.