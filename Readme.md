# Distributed recommender engine for social media giant.

We have built a recommender engine to predict the likelihood of a user following a particular account.

## Data
Tencent Social Media [Data](https://www.kaggle.com/competitions/kddcup2012-track1/data)


## Outline  
1. Loaded the data from AWS S3 and preprocessed 73 million rows of social media data using Spark and stored in MongoDB Atlas.
2. Generated keyword embeddings using word2vec architecture on user’s activity data and applied logistic regression to predict the likelihood of a user following an account. 

