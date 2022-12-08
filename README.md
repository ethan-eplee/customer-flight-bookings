# Inventory Forecasting

 - [Problem Statement](#Problem-Statement) 
 - [Data Sources](#Data-Sources)
 - [Executive Summary](#Executive-Summary)
 - [Reflections](#Reflections)


## Problem Statement
- To web scrap customer reviews from Skytrax, an airline rating site, to gather business insights 
- To build a high quality predictive model to predict successful bookings using customer bookings data

--- 
## Data Sources
- Third party customer reviews on Skytrax
- Customer flight bookings data consisting of 50,000 rows and 13 features

---
## Executive Summary
**INTRODUCTION**

This project is part of British Airways's (BA) virtual internship. BA is the flag carrier of the United Kingdom, carrying thousands of customers around the world each year to and from the UK. There are two tasks here. Firstly, to web scrap customer reviews from Skytrax, an airline rating site, to gather insights and secondly, to build a high quality predictive model to predict successful bookings using customer bookings data.

**Overview of Project**
- Scraping and collecting unstructured data in the form of customer reviews from [Skytrax](https://www.airlinequality.com/airline-reviews/british-airways), a third-party airline review website
- Cleaning the data extensively using NLP techniques and feature engineering of text data
- Performed EDA on cleaned data to gather insights on customer's feelings, needs and feedback
- Data visualizations using charts, word clouds and distribution plots to communicate findings
- Using customer bookings data provided by BA to perform analysis and modelling to predict customers making a flight booking
- Used RandomForest and XGBoost classifiers to come up with an interpretable working model
- Plotted the feature importance to visualize how each variable contributes to the predictive power of the model

**Skills Learnt**
- Webscraping using the BeautifulSoup library to obtain data from a third-party source
- Working with an imbalanced dataset that has a 15% positive class
- Using NLP tools such as tokenizers, lemmatizers and stopwords

---
## Reflections
Collecting data via webscraping was always bound to be messy and it gave me a glimpse of what it is to work with unstructured and text data in a real-world environment. Subsequent steps of using NLP techniques to gather insights also made the task challenging. I believe that further insights can be gained from cleaning the data further, or using more advanced NLP tools to conduct sentiment analysis.