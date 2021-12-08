# NLP HW

Use sentiment analysis on Bitcoin and Ethereum news articles. Explore other factors involved with the coin prices such as common words and phrases and mentioned organizations and entities.

[Starter Notebook](Starter_Code/crypto_sentiment.ipynb)

## Instructions

### 1 - Sentiment Analysis

Use the [newsapi](https://newsapi.org/) to pull the latest news articles for Bitcoin and Ethereum. For each coin, create a df of sentiment scores.

Use descriptive stats to answer the following questions:

> Which coin had the highest mean positive score?
>
> Which coin had the highest negative score?
>
> Which coin had the highest positive score?

### 2 - Natural Language Processing

For both coins, use NLTK and Python to tokenize text, find n-gram counts, and create word clouds.

#### Tokenize

Be sure to:

1. Lowercase each word.
2. Remove punctuation.
3. Remove stop words.

#### N-grams

For each coin:

1. Use NLTK to produce the ngrams (N = 2).
2. List each coin's top 10 words.

#### Word Clouds

Generate word clouds for each coin.


### 3 - Named Entity Recognition

Build a named entity recognition model for both coins. Visualize the tags using SpaCy.

### Resources

[Vader Sentiment Analysis](http://www.nltk.org/howto/sentiment.html)


### Hints and Considerations

The free developer version of the News API limits the total daily requests, so be careful not to exceed the free limits.
