---
title: '5a: Learning data analysis (part 1)'
---
The letter **"T"** is an apt symbol of what to learn. The horizontal line of the __T__ represents learning broadly, while the vertical line is learning deeply. A __"T"__ shaped person is capable in many things and an expert in at least one.



![8dcfeb5422c346ae6c9594f09b5eefed6fcdbc9e.png](8dcfeb5422c346ae6c9594f09b5eefed6fcdbc9e.png)

We've broadly learned about programming concepts in the previous section - skills that will come in handy in future. Let's now dive deep into the tools used by a data analyst.

## Pandas

Pandas is the most popular data analysis library in Python. A data analysis library helps you easily manipulate data. You'll use Pandas to explore data, or to transform data to what you want. 

Pandas makes life simple by abstracting away the steps needed for a calculation. You'll normally take two steps to fill in a column of data with some null values: 

(a) filter for just the null values and then 

(b) specify another value to replace the nulls

Pandas has a specific method called `fillna`, which helps you fill nulls in a single step by just typing `fillna(value=0)`. This fills nulls with 0. Or fill it with other value you want. 

This is how abstraction makes complicated tasks easier. By combining many steps into a single command. This is especially useful with tasks that require more steps. 



Some flavour of what Pandas does:

* Read and write many data formats (csv, xlsx, JSON, text, html)
* Filter data using specific conditions (to look at data from June to December for example)
* Calculate across rows or columns (sum, average, mean)
* Find and fill missing data
* Reshape data
* Time series calculations
* Basic visualization of data (visualization using Pandas is basic and it's built on top of a more comprehensive library called `matplotlib`)



### How to learn Pandas

The explicit goal is not to "learn Pandas". It's to use Pandas as a tool for something more meaningful. 

To process data to make an informed decision that saves your company $300,000 annually for example. 

Learning Pandas for it's own sake won't be as useful as learning Pandas in a way you'll actually use for data analysis.



If this is your first encounter with Pandas, you're at level 0: not knowing what you don't know. We'll use the same process I outlined in Chapter 3 to learn Pandas. 

Start broad. Learn a large number of things you can do with Pandas. But keep learning shallow. I love using video courses when I first start learning. I find video much less boring than reading docs at the start. Video gives a good overview and builds intuition. 

Watching a video course gives you hooks to latch onto when you start using Pandas without guided tutorials. You'll know what to Google and where to look. 



I found [this Udemy course](https://www.udemy.com/course/data-analysis-with-pandas/) an excellent starter Pandas resource. Udemy courses are less than $20. I pay a small amount for starter resources, just because they help me save time getting started. Time is precious. Time is also money.



### Clean, explore and visualize data

__Clean__

Besides learning the mechanics through Pandas, you should also learn how to clean and explore data. 

Working with clean data is important. Drawing insights from dirty data might be misleading. Cleaning data mostly involves knowing what pitfalls to look out for. [This short course](https://www.kaggle.com/learn/data-cleaning) on Kaggle is an excellent resource to follow along. 

What is [Kaggle](https://www.kaggle.com/)? It's a website which has datasets, data science competitions, and tutorials. Kaggle also has notebooks. Notebooks allow you to run code in your browser, on Kaggle's servers. [This tutorial](https://www.kaggle.com/c/titanic) shows you how to use Kaggle's platform. We will be using Kaggle more later.

Kaggle's focus is on machine learning, but many exercises on Kaggle are relevant for data analysis.



__Explore__

Data is explored after cleaning. This means doing an exploratory data analysis, or EDA for short. 

EDA is a journey. First ask questions you want answers to, and then use different methods to explore data. The goal of an EDA is to better understand the data you're working with. To test assumptions you might have at the back of your mind.  

Howard Seltman is a professor at Carnegie Mellon. He wrote an excellent chapter on EDA which you can find [online here](https://www.stat.cmu.edu/~hseltman/309/Book/chapter4.pdf). It's free. The chapter is a tad more technical, which might make your head hurt. Your head hurts when your brain chunks new concepts. It's a good thing as it means you're growing.



__Visualize__

You will be a better data communicator through visualization. Most people are not data nerds. They can't conjure up patterns in the data when they look at a chunk of numbers. Simplifying data through visualizations helps other people connect with your data. 

Visualizing data also helps you detect patterns, trends, and correlations that you might otherwise miss. 

In the Udemy Pandas course above, you've briefly covered visualizations. It's worth spending just a bit more time to get the basics down. It's more important to know **_what_** to visualise. You can always google how to plot something once you know what to plot. 

I made notes of the plots depending on the data that you have. Plotting numerical data is different from categorical data. But what if you want to plot both numerical and categorical in the same graph? [Check it out here.](https://www.evernote.com/shard/s349/sh/173a5d15-35fc-48e0-b441-b6af04beed38/e157d7bcbbe84e13ddafd4345257dfe5) 

There are many tutorials that teach you how to plot graphs in Python. Having a basic understanding of how plots work is useful. You can then read other people's code and understand what each line does. I recommend you to learn the bare minimum to start making plots. Then start reading other people's code to build upon your base. 

There are two resources I found ideal for starters:

1. [Data visualization with Python course on Coursera](https://www.coursera.org/learn/python-for-data-visualization#syllabus). It covers Matplotlib which is a Python library for visualisations. Many other libraries are built on top of Matplotlib. Learning Matplotlib first helps you to understand how many other visualisation libraries in Python work
1. [Basic data visualization tutorial](https://www.kaggle.com/learn/data-visualization) on Kaggle here. This teaches you Seaborn basics. Seaborn is built on top of Matplotlib. Seaborn makes plotting nice graphs easier, and with less code than Matplotlib



### Let's practice

After completing the above resources, you'll have climbed from: 

level 0: don't know what you don't know, to

level 1: knowing what you don't know



Since we're now at level 1, let's shift from "just in case" shallow learning to "just in time" learning.

It's now time to put what you learnt into practice. Kaggle is a good place to start your own exploratory data analysis. 

How do you start? By picking a Kaggle dataset. Choose a dataset that you're interested in. Remember that having fun is important? 



You can pick Kaggle competition datasets or through user submitted datasets. I recommend starting with a competition dataset. 

Thousands of teams have invested effort in competitions as there is prize money. You'll have many other notebooks to compare your analysis to. 

But only look at other notebooks when you are done. Spending the mental effort and first iterating on your own analysis is tougher. But it helps you grow much faster. After you've had a first go at an analysis, read as many other notebooks as you can. Find the ones with "EDA" and have many upvotes. These notebooks often explain themselves well.

Blend your work and their work after into a single notebook. See what you've missed out. 



Don't forget to clearly annotate your notebook. The general rule is the more explanation text the better. The notebook should be clear enough for someone without context to skim and understand.

Why take the trouble? This forms part of your portfolio, where you use your learning to show employers your capabilities. People want to read code that's easy to understand. It helps to build your portfolio over time, and not just though a single capstone project. One project is likely not enough. 

Think of each project as a bet. Placing many bets gives you a diversified portfolio; you'll have options. You can choose to put your best projects in your resume, or the most relevant one to the role you're applying for. 

But we're getting a bit ahead of ourselves. I'll cover interview strategy in great detail later. 



### Some useful tips

A few more tips when you're practising. 

Write down the end state you hope to achieve before you code. 

For example, I track my daily spend and record thousands of individual transactions each year. After each year, I have a personal dataset to analyse for insights. Reviewing the transactions is just a middle step. The end goal is to see which spending categories I should cut down or spend more on. I might conclude to spend less on food and more on entertainment, as spending more on entertainment breaks life's monotony and gives me better stories to tell. 

Defining goals beforehand gives your analysis purpose. The alternative is to fly blind through an analysis, which is unmotivating and unimaginative. Purpose is like having a map that guides you through unfamiliar terrain - it's invigorating.



The next step is understanding the data. Say you're looking at Amazon's e-commerce purchase data. What does each row represent? Is each row an order, or an item in an order? 

This point might seem too trivial to mention. But I've seen this mistake more than I'd like. 

How do I know? I've administered a fair share of take home case studies during interviews. Many candidates don't bother to check what a row in the dataset represents. They end up grouping data as if each row were an order, when in fact each row _is an item in an order_. 

In technical speak, this means identifying the granularity or grain of the data. The grain is the finest level of detail that is implied. It's especially important when doing an analysis or when joining different data sources together.

Misinterpreting data is grave mistake that cannot be overlooked. Any conclusions drawn will be inaccurate at best, and detrimental at worst. Harmful decisions could be made from misinterpreted data.



We're done with data analysis. Let's see what's next. 



