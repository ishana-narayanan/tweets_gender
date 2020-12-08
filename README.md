# Gender Classification From Twitter Data

## Emi Kong, Ishana Narayanan, Jacqueline Zhang

In this project, we used Twitter data to predict the gender of Twitter users. Our gender classification was multiclass with a user being labeled male, female or brand. The features we considered in our models included term frequencies, punctuation counts, emoji appearance, account years, number of total tweets, retweets, and favorites. We utilized many Feature Transformers from the ML Features package and built pipelines to clean and preprocess the dataset. Our models included Multinomial Logistic Regression, Random Forest, Naive Bayes, and KMeans. Using compute time and confusion matrix metrics to evaluate each model, we found that our Benchmark model of Multinomial Logistic Regression with term frequency for each tweet as the input parameter has the best accuracy and compute time. Therefore, our Benchmark model is our champion model. However, the accuracy is not impressive and thus we cannot fully predict the gender of Twitter users just from tweet and certain account information.

## Read full report [here](https://github.com/ishana-narayanan/tweets_gender/blob/main/Gender%20Tweets.pdf)

