# Emotion Detection in Twitter Feeds with Neural Networks

# Group number 2
* Asnova Jahan Reana (2021-2-60-093)
* Yougshree Saha Urmy (2021-1-60-127)

# Dataset
* Dataset taken from Kaggle: https://www.kaggle.com/datasets/dimonyara/additional-dataset-for-emotions](https://www.kaggle.com/datasets/pashupatigupta/emotion-detection-from-text/data
* It contains 3 columns and 40,000 rows
* The size of the file is 3.59 MB
* The columns are content and sentiment
* The content column contains random tweets from various users
* The sentiment column contains 13 emotions from those tweets: neutral, worry, happiness, sadness, love, surprise, fun, relief, hate, empty, enthusiasm, boredom, anger
* If we need to increase the amount of tweets for the dataset we can try extracting tweets from Twitter through web-scraping
* Those tweets would need to be pre-processed, which would involve removing twitter id, handles, special characters, hyperlinks, etc.

# Proposed Methodology
* The dataset would be split into training and test sets, 80-20
* We plan on using the architecture LSTM on the dataset
* After training the model we would test and get the accuracy for the model
