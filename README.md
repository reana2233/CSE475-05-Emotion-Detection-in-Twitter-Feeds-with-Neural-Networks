# Emotion-detection-from-tweets-using-Convolution-Neural-Networks

# Group number 2
* Asnova Jahan Reana (2021-2-60-093)
* Yougshree Saha Urmy (2021-1-60-127)

# Dataset
* Dataset taken from Kaggle: https://www.kaggle.com/datasets/dimonyara/additional-dataset-for-emotions
* It contains 2 columns and 20,000 rows
* The size of the file is 1.97 MB
* The columns are content and sentiment
* The content column contains random tweets from various users
* The sentiment column contains 13 emotions from those tweets: neutral, worry, happiness, sadness, love, surprise, fun, relief, hate, empty, enthusiasm, boredom, anger
* If we need to increase the amount of tweets for the dataset we can try extracting tweets from Twitter through web-scraping
* Those tweets would need to be pre-processed, which would involve removing twitter id, handles, special characters, hyperlinks, etc.

# Proposed Methodology
* The dataset would be split into training and test sets, 70-30
* We plan on using the architectures Inception and ResNet separately on the dataset
* After training the models we would test them and get the accuracy for these 2 models
* We would compare the accuracy of the models after running them on the test set
