# Intro to Data Wrangling
This project is part of the Udacity Data Analyst Nanodegree program.

Project 2: Wrangle-and-Analyze-Data

Udacity logo
Udacity Data Analyst Nanodegree

Table of contents

    Introduction
    Project Details
    Gathering Data for this Project
    Assessing Data for this Project
    Cleaning Data for this Project
    Storing, Analyzing and Visualizing Data for this Project
    Installation
    Requirements
    Author

Introduction

Real-world data rarely comes clean. Using Python and its libraries, In this project we will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness.

The dataset that you will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

alt text
Project-Details

Your tasks in this project are as follows:

    Data wrangling, which consists of:
        Gathering data
        Assessing data
        Cleaning data

    Storing, analyzing, and visualizing your wrangled data

    Reporting on 1) your data wrangling efforts and 2) your data analyses and visualizations

Gathering-Data-for-this-Project

Gather each of the three pieces of data as described below in a Jupyter Notebook titled wrangle_act.ipynb:

    The WeRateDogs Twitter archive twitter_archive_enhanced.csv. It's instructed that this file be downloaded manually from an URL provided by Udacity.
    The tweet image predictions, i.e., what breed of dog (or other object, animal, etc.) is present in each tweet according to a neural network. This file (image_predictions.tsv) hosted on Udacity's servers and should be downloaded programmatically using the Requests library and the following URL: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv
    Each tweet's retweet count and favorite (i.e. "like") count at minimum, and any additional data you find interesting. Using the tweet IDs in the WeRateDogs Twitter archive, query the Twitter API for each tweet's JSON data using Python's Tweepy library and store each tweet's entire set of JSON data in a file called tweet_json.txt file. Each tweet's JSON data should be written to its own line. Then read this .txt file line by line into a pandas DataFrame with (at minimum) tweet ID, retweet count, and favorite count.

Assessing-Data-for-this-Project

After gathering each of the above pieces of data, assess them visually and programmatically for quality and tidiness issues. Detect and document at least eight (8) quality issues and two (2) tidiness issues in your wrangle_act.ipynb Jupyter Notebook. To meet specifications, the issues that satisfy the below mentioned Key Points must be assessed.
Cleaning-Data-for-this-Project

Clean each of the issues you documented while assessing. Perform this cleaning in wrangle_act.ipynb as well. The result should be a high quality and tidy master pandas DataFrame (or DataFrames, if appropriate).
Storing-Analyzing-and-Visualizing-Data-for-this-Project

Store the clean DataFrame(s) in a CSV file with the main one named twitter_archive_master.csv. If additional files exist because multiple tables are required for tidiness, name these files appropriately. Additionally, you may store the cleaned data in a SQLite database (which is to be submitted as well if you do).

Analyze and visualize your wrangled data in your wrangle_act.ipynb Jupyter Notebook. At least three (3) insights and one (1) visualization must be produced.
