# HERA

- Part of: Google Bangkit 2021 Capstone Project
- Task: Sexual Harassment Classification System

# HERA Data Preprocessing, Modeling, and Sexual harassment Classification

HERA (Helps and Emergency Reporting App) is an Android-based application which provides online complaint service and prevention against women's violence and harassment. HERA mainly solves problems during pandemic conditions, namely the unreadiness of a complaint service model for pandemic conditions (not yet adapted to turning complaints online) and large-scale social restrictions (PSBB) which largely impacted the decrease of report amount in various service agency.

Two Convolutional Neural Networks were trained to classify user posts in the "Speak Up!" feature and report types in "Online Report" based on descriptions. Tweets from the #MeToo movement on Twitter (now X) served as training data, with labels assigned via RegEx keyword matching. The models achieved 80.26% accuracy for posts (6 categories) and 78.24% accuracy for reports (7 violence-related categories).

## What is in my project...

This project are consists of 3 parts:
1) Data Cleaning, intended to clean the scraped dataset from the unwanted character such as symbols and any others inconsistencies.
2) Data Labeling, intended to give the label to each sentence in the dataset based on defined keywords, since it were unlabeled when scraped.
3) Data Modeling, intended to develop deep learning model to classify the user reports and posts.

## What is in the dataset...

The dataset were 16.200+ sentence scraped from Twitter (now X) using Kafka, Tweepy, and Twitter API. The selected tweets to be scraped were the tweets which has the #MeToo hashtag in the post.
The dataset only have one column, which consists of the user post's sentence. Later on, two columns are added through data labeling, which shows the category of the user posts and reports classification.

## Result of this project...

Two Convolutional Neural Networks were trained to automatically classify user posts in the "Speak Up!" feature and report types in the "Online Report" feature based on the user’s description. Tweets from the #MeToo movement in Twitter (now X) were scraped as the training data.

Labels were determined by the defined keywords that exist in the tweets using RegEx. After several tuning processes, an accuracy of 80,26% was achieved for posts classification with 6 categories and 78,24% accuracy for report classification with 7 categories related to violence type.

## What should I improve next...
1. Try to collect more data from the related hashtag or other sources.
2. Fix the data cleaning mechanism, since dirty data might not preprocessed, or the data are too much preprocessed which makes another nonsense word.

## My resources...
1. A lot of Google searches, for defining the labels and related keyword
2. Stack overflow to debug the problems
