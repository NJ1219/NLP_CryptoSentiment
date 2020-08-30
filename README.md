# NLP Project—Tales from the Crypto

![Stock Sentiment](Images/sentimental.jpeg)

## Background

There's been a lot of hype in the news lately about cryptocurrency, so one would want to take stock, so to speak, of the latest news headlines regarding Bitcoin and Ethereum to get a better feel for the current public sentiment around each coin.

In this project, natural language processing was applied to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. A few fundamental NLP techniques were applied to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

The following tasks were completed:

1. [Sentiment Analysis](#1---Sentiment-Analysis)
2. [Natural Language Processing](#2---Natural-Language-Processing)
3. [Named Entity Recognition](#3---Named-Entity-Recognition)

---

## Files

[Starter Notebook](Starter_Code/crypto_sentiment.ipynb)

---

## Instructions

----

### 1 - Sentiment Analysis

The [newsapi](https://newsapi.org/) was used to pull the latest news articles for Bitcoin and Ethereum and create a DataFrame of sentiment scores for each coin.

Using descriptive statistics the following questions were answered:

> Which coin had the highest mean positive score?
>
> Which coin had the highest negative score?
>
> Which coin had the highest positive score?

---

### 2 - Natural Language Processing

In this section, NLTK and Python were used to tokenize text, find n-gram counts, and create word clouds for both coins. 

#### Tokenize

It was made sure to:

1. Lowercase each word
2. Remove punctuation
3. Remove stop words

#### N-grams

Next, the ngrams and word frequency for each coin was looked.

1. NLTK was used to produce the ngrams for N = 2.
2. The top 10 words for each coin were listed.

#### Word Clouds

Finally, word clouds were generated for each coin to summarize the news for each coin.

![btc-word-cloud.png](Images/btc-word-cloud.png)

![eth-word-cloud.png](Images/eth-word-cloud.png)

---

### 3 - Named Entity Recognition

In this section, a named entity recognition (NER) model was built for both coins and were visualized to the tags using SpaCy.

![btc-ner.png](Images/btc-ner.png)

![eth-ner.png](Images/eth-ner.png)

---

## Resources

[Vader Sentiment Analysis](http://www.nltk.org/howto/sentiment.html)

---

# NLP_CryptoSentiment