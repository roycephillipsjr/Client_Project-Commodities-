# Client_Project-Commodities-
Client Project to find available commodities during COVID-19

## Problem Statement


## Executive Summary
Looking through this notebook you can see all the information you need to find on how I came to my conclusion. The data was created by pulling the information from Pushshift's Reddit API(https://github.com/pushshift/api). The dataset was then created from my initial pull and then I cleaned and parsed the data to fit it into a model.


Below you can see all the resources and the work that was done on the data. It includes:
1. 5 jupyter notebooks
2. The data sources I created and the cleaned csv.
3. The Pushshift API I used
4. The subreddits I referenced
5. A data dictionary
6. The procedure and methodology
7. The conclusion

## Contents:

- [Data Gathering](01_Data_Gathering.ipynb)
- [Data Cleaning and EDA](02_Data_Cleaning_EDA.ipynb)
- [Further Cleaning](03_Further_Cleaning.ipynb)
- [Modeling](04_Modeling.ipynb)
- [More Data Visualization](05_Visualizations.ipynb)
- [Project 3 Reddit Classification PPT](Project_3_Reddit_Classification.pdf)

## Data sources:
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
