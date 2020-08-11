# Happy to share ideas in data science

## [06/2020: Two-stage-models to extract tweet sentiment](https://www.kaggle.com/emily2008/tweet-sentiment-extraction-2-stage-models)
**key words: Roberta&CNN, WordPiece&character hybird embedding, two-stage-models**

The first stage model relies on Roberta transformer and CNN to predict the start and end token index of sentiment in the wordpiece token sequence of tweet. The second stage model is based on character_level embeddings and CNN to futhur compute the start and end index of sentiment.The implementation of the second stage model significantly impoved the [jaccard score](https://en.wikipedia.org/wiki/Jaccard_index) from 7.13 to 7.26.

## [08/2019: Quora Insincere Question Identification](https://www.kaggle.com/emily2008/quora-insincere-questions)
**key words: Sentiment analysis, LSTM, Attention, kaggle competition**

Build and train LSTM model with Attention mechanism to identify Quora insincere questions. Programmed with python and keras. The score ranks in the top of 16% out of 4037 teams.

## [01/2019: Use news and market state to predict stock trend](https://www.kaggle.com/emily2008/two-sigma-stock-news-market?scriptVersionId=7345306)
**key words: LightGBM, news&market state, kaggle competition**

Build a LightGBM model to predict how stocks will change based on the market state and news articles. The outcome performance ranks in the top  of 4% out of 2927 teams.
