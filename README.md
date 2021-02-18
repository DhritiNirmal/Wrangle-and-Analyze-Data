# Wrangle-and-Analyze-Data
Introduction

The purpose of this project is to put into practice what I learned in the data
wrangling section from Udacity Data Analyst Nanodegree program. The dataset
that is wrangled is the tweet archive of Twitter user @dog_rates, also
known as WeRateDogs. WeRateDogs is a Twitter account that rates people's
dogs with a humorous comment about the dog. These ratings almost always
have a denominator of 10.
This report briefly describes my wrangling efforts.
Project details

The tasks of this project are as follows:
• Gathering data
• Assessing data
• Cleaning data

Gathering data
The data for this project consist on three different dataset that were obtained as
following:
• Twitter archive file: the twitter_archive_enhanced.csv was provided by
Udacity and downloaded manually.
• The tweet image predictions, i.e., what breed of is present in each tweet
according to a neural network. This file (image_predictions.tsv) is hosted
on Udacity's servers and was downloaded programmatically using the
Requests library and URL information
• Twitter API & JSON: by using the tweet IDs in the WeRateDogs Twitter
archive, I queried the Twitter API for each tweet's JSON data using
Python's Tweepy library and stored each tweet's entire set of JSON data
in a file called tweet_json.txt file. I read this .txt file line by line into
a pandas dataframe with tweet ID, favorite count, retweet count,
followers count, friends count, source, retweeted status and url.

I used Python programming language and some of its packages.
• For gathering data there are several packages that help scraping data off
the web, that help using APIs to collect data (Tweepy for Twitter) or to
communicate with SQL databases.
• It is strong in dealing with big data (much better than Excel). • It can
deal with a large variety of data (unstructured data like JSON
(Tweets) or also structured data from ERP/SQL databases.
• It is easy to document each single step and if needed re-run each single
step. Thus, one can leave a perfect audit trail (perfect for the accountant). •
One can re-run analysis automatically every period. Thus, we could actually
re-run the dog analysis every month with much less effort now because I
have set it up once.
• Handling, assessing, cleaning and visualizing of data is
possible programmatically using code.
