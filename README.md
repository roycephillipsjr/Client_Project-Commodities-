
[Photo Source](https://www.furman.edu/covid-19/)

# Client Project Finding Available Commodities
Client Project to find available commodities during COVID-19

## Team Members 
[Jeong Huh](https://www.linkedin.com/in/jeong-huh/)
<br>[Royce Phillips Jr](https://www.linkedin.com/in/roycephillipsjr/)

## Problem Statement


## Executive Summary
Looking through this notebook you can see all the information you need to find on how our team worked to find available commodaties during the COVID-19 pandemic. The data was created by pulling the information from [Twitters developer's API](https://developer.twitter.com/en/docs). The dataset was then created from those tweets that were pulled and then cleaned, parsed, and fit into a DBSCAN model. The geo coordinates that were found were then put on Google maps using a [Google map API](link).


#### Below you can see links to the jupyter notebooks, data, and references:

## Jupyter Notebooks:

- [Data Gathering](00_Gathering_tweets.ipynb)
- [Gathering Coordinates](01_Gathering_coordinates.ipynb)
- [Cleaning tweets](02_Cleaning_tweets.ipynb)
- [Preprocessing and Modeling](03_Preprocessing_Modeling.ipynb)


## Data:
- [Original Tweets](datasets/all_commodities_tweets.csv)
- [Origian Tweets with Cleaned Tweets](Datasets/cleaned_tweets.csv)


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
