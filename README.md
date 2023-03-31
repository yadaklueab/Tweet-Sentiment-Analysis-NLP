# Tweet-Sentiment-Analysis-NLP

![](Screen Shot 2566-03-31 at 13.43.50.png)

Every day, social media platforms such as Twitter, Facebook, and Instagram generate billions of lines of text. This text is mostly unstructured data, making it difficult and time-consuming to interpret using traditional methods. However, text classification with machine learning can bridge this gap by allowing us to automatically categorize and analyze this data more efficiently. The Kaggle competition, Tweet Sentiment Extraction (https://www.kaggle.com/competitions/tweet-sentiment-extraction), offers an insightful opportunity to explore the practical application of Natural Language Processing (NLP). The competition entails picking out the part of the tweet (word or phrase) that reflects the sentiment. In this project, instead, I will several NLP techniques to classify tweets into three categories: "positive," "neutral," and "negative," I picked out a rule-based SentimentIntensity Analyzer as a baseline, the combination of Bag-of-words (tf-idf) and Logistic Regression, the combination of Elmo and Logistic Regression, and BERT.

## Dataset

The dataset used contains the text and sentiment of the tweet from Kaggle competition, Tweet Sentiment Extraction. This task includes one file which is train.csv. Each row in the training contains the text of a tweet and a sentiment label and also provided with a word or phrase selected from the tweet (selected_text) that encapsulates the provided sentiment.

The columns included in the dataset are as follows:
textID: A unique identifier for each piece of text\
text: The text of the tweet\
sentiment: The general sentiment of the tweet\
selected_text: The text that supports the tweet's sentiment \

This dataset contains a total of 27,481 example rows for the training set. In the training set, the data includes textID to identify for each piece of text, text of tweet, sentiment, which can be classified into negative, neutral, and positive, and select_text, which is the text that supports the tweet’s sentiment and this column is only available in the training set. 


## Collaborator
Yada Klueabvichit\
MaoHo Wang
