# Client_Project-Commodities-
Client Project to find available commodities during COVID-19

## Problem Statement


## Executive Summary
Looking through this notebook you can see all the information you need to find on how our team worked to find available commodaties during the COVID-19 pandemic. The data was created by pulling the information from Twitters developer's API(https://developer.twitter.com/en/docs). The dataset was then created from those tweets that were pulled and then cleaned, parsed, and fit into a DBSCAN model. The geo coordinates that were found were then put on Google maps using a Google map API(link).


#### Below you can see links to the jupyter notebooks, data, and references:

## Contents:

- [Data Gathering](01_Data_Gathering.ipynb)
- [Data Cleaning and EDA](02_Data_Cleaning_EDA.ipynb)
- [Further Cleaning](03_Further_Cleaning.ipynb)
- [Modeling](04_Modeling.ipynb)
- [More Data Visualization](05_Visualizations.ipynb)
- [Project 3 Reddit Classification PPT](Project_3_Reddit_Classification.pdf)

## Data:
- [Original Reddit Dataset](Datasets/big_reddit_list.csv)
- [Reddit Dataset with Feature Engineered columns](Datasets/reddit_list_with_feature_engineering.csv)
- [Reddit Dataset with added sentiment analysis](Datasets/reddit_cleaned_title_and_selftext.csv)


##  References
- [Twitter](https://twitter.com/)
- [Twitter API](https://developer.twitter.com/en/docs)
- [Twitter API Tutorial](http://socialmedia-class.org/twittertutorial.html)
- [Source Code for gathering tweets](https://www.youtube.com/watch?v=WX0MDddgpA4&list=PL5tcWHG-UPH2zBfOz40HSzcGUPAVOOnu1&index=3)
- [Tweepy Documentation](http://docs.tweepy.org/en/v3.8.0/index.html)
- [Github reference](https://github.com/TungPhung/Twitter-Natural-Disaster-Mapping/blob/master/ProcessingandModeling.ipynb) Used as a resource for how to use modeling in tweets




Feature|    Type|    Dataset|Data Retrieved From|Description|
-------|--------|-----------|-------------------|-----------|
**tweets**|object|cleaned_tweets|Twitter API|text of the tweet|
**id**|float|cleaned_tweets|Twitter API|id of the tweet|
**name**|object|cleaned_tweets|Twitter API|name of twitter page|
**location**|object|cleaned_tweets|Twitter API|location of twitter page|
**coordinates**|object|cleaned_tweets|Twitter API|coordinates of where tweet was posted|
**created_at**|object|cleaned_tweets|Twitter API|when the tweet was created|
**favorite_count**|float|cleaned_tweets|Twitter API|how many people favorited the tweet|
**geo**|object|cleaned_tweets|Twitter API|geo location of tweet|
**source**|object|cleaned_tweets|Twitter API|the source where tweet came from|
**clean_tweets**|object|cleaned_tweets|Twitter API|cleaned tweets, removed characters|



## Procedure/Methodology


# Conclusion
