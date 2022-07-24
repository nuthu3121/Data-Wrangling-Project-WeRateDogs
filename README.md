# Data-Wrangling-Project-WeRateDogs
This is the second project in the udacity data analyst nano degree program. It involves data gathering and wrangling 

## Introduction

Real-world data rarely comes clean. This project required one to use python and it libraries to  gather data from a variety of sources and in a variety of formats, 
assess its quality and tidiness, then clean it. One was also required to all data wrangling efforts n a Jupyter Notebook, and showcase them through analyses and visualizations using Python
and its libraries.

## Datasets

The dataset used in this project was the tweet archive of Twitter user [@dog_rates](https://twitter.com/dog_rates), 
also known as [WeRateDogs](https://en.wikipedia.org/wiki/WeRateDogs). WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog.
These ratings almost always have a denominator of 10. However, the numerators are almost always greater than 10. For instance, the following are some of the dog ratings
11/10, 12/10, 13/10, etc. In this project, we worked on the following 3 datasets

***[Enhanced Twitter Archive](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/59a4e958_twitter-archive-enhanced/twitter-archive-enhanced.csv)***

The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets, but not everything. One column the archive does contain though:
each tweet's text, which was used to extract rating, dog name, and dog "stage" (i.e. doggo, floofer, pupper, and puppo)
to make this Twitter archive "enhanced." Of the 5000+ tweets. This data had been filtered for tweets with ratings only (there are 2356).

***Additional Data via the Twitter API***

This additional data was gathered from Twitter's API. Using the Twweet IDs in the `Enhanced Twitter Archive` dataset, we gathered this data for all 5000+.  
**NB** if you're unable to download this file using API, it is provided in this repository as `tweet_json.txt`

***Image Predictions File***

This file `image_predictions.tsv` was present in each tweet according to a neural network. It was hosted on Udacity's servers and was to be downloaded 
programmatically using the Requests library and the 
following URL: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv

## What do I need to install?

You will need to have python installed as well as the following python libraries.

- pandas
- NumPy
- requests
- tweepy
- json


