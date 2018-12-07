
# MSAN 621 Final Project

Team: Data Explorers

Team members: 

* Adam Reevesman
* Gokul Krishna Guruswamy
* Hai Le
* Maximillian Alfaro
* Prakhar Agrawal

# Resources in this repository

Finalized notebooks are: 
* [Data processing and feature engineering code](data_processing/data_processing.ipynb)
* [Data scraping code](data_processing/extract_Data.ipynb)
* [List of final features for model fitting](data_processing/features.md)
* [Model fitting and model comparison](model_fitting/model_fitting.ipynb)

The draft code is saved here for the purpose of future review [/drafts]

# Objective

To predict how many __upvotes__ a comment will get, given the comment text, user history, sub-reddit and thread details.

# Data Source

We use 2 sources of data: 

* Comments Dataset [available here](https://mega.nz/#F!NtsCGTgD!urXdXLJ6yITYdWEdWN-H1w)
* Threads Dataset scraped using Reddit API using [this code](/scraping/Scrape.ipynb)

# Reference Papers/Write-ups

* [Predicting Comment Karma on Internet Forums](http://cs229.stanford.edu/proj2014/Daria%20Lamberson,Leo%20Martel,%20Simon%20Zheng,Hacking%20the%20Hivemind.pdf)
* [Predicting Comment Karma by Subreddit](http://yoavz.com/reddit_karma.pdf)
   - github link concerning [this paper](https://github.com/yoavz/predict_reddit_comments) 
   
# FAQ about reddit

* [what is karma](https://www.reddit.com/r/NoStupidQuestions/comments/2idfhk/what_is_link_karma/)
* [what is reddit](https://www.reddit.com/wiki/faq)
