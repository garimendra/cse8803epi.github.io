# Predicting DogeCoin Price Bubbles using Epidemic Modeling

For CSE-8803 : Data Science for Epidemiology by Dr. B. Aditya Prakash, Fall 2021

Steps for runnning the notebooks - 

Twitter Sentiment Analysis 

1. Tweets are collected using python's TWINT library which allows us for ftching raw tweets with keywords in the set ["doge", "#doge", etc.]
2. The duplicates are removed and tweets are cleaned to perform lemmatization and tokenization of the tweets. 
3. Finally after removing the unwanted symbols, sentiment analysis is performed for the tweets to be assigned a score based on the NLTK library. 
