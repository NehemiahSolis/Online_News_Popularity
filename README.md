# Online News Popularity: Predictive Modeling with Machine Learning

## Project Overview

In this era of information and expansion of the internet, an ever-increasing number of people enjoy reading and sharing online news articles. They can be spread and shared instantly, with people sharing articles on facebook, twitter, and other social media sites. 

Online news sites like Medium, Buzzfeed, and Mashable publish hundreds of articles every day, and their revenue comes from several different sources. The most common source is “Cost per click”, an advertising term where the advertiser “pays a cost to a publisher for every click” on their ad. The more readers visit a site, the more likely someone will interact with the ad and make the site money. A good way to gauge article popularity and reader interaction is through how many times that article has been shared. For some quick background on the digital media website that I will be using to build my predictive models, Mashable Inc was founded in 2005, and has 9.7 million Twitter followers and 7.5 million Facebook fans. Essentially, they have an enormous following, so being able to predict the popularity and maximize the amount of shares before publication would be greatly helpful for Mashable, or any site, and their media workers (authors, advertisers, etc) 

## Problem Statement

Predicting the popularity of news can be approached in several ways. At first glance, the target variable, which is “shares”, indicates a regression problem. However, you can solve this problem with classification.

Essentially, there are two, similar hypothesis: We can use regression tasks to say “Given the features of an article, we can predict the number of times an article is shared”. We can also use classification tasks say “Given the features of an article, we can predict whether or not an article will become popular or not.” 

In addition, we will want to optimize those given features needed to address the hypothesis. 

## Dataset Description

The dataset I will be using was originally compiled by Kelwin Fernandes and associates from the University of Porto in Portugal over a span of two years, from 2013 to 2015. It has already been pre-processed. For example, for the categorically variables, they have already been transformed by one-hot encoding and skewed features (like number of words in the article) have already been log transformed. 

### For an Overview of the Project visualizations and Results, please refer to the [Slide Presentation](https://github.com/NehemiahSolis/Online_News_Popularity/blob/master/Online%20News%20Popularity.pdf) and the [Jupyter Notebook](https://github.com/NehemiahSolis/Online_News_Popularity/blob/master/Online_News_Popularity%20(1).ipynb)
