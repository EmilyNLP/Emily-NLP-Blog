# Happy to share ideas in data science

## [2020-06: Two-stage-models to extract tweet sentiment](https://www.kaggle.com/emily2008/tweet-sentiment-extraction-2-stage-models)
**key words: Roberta&CNN, WordPiece&character hybird embedding, two-stage-models**
The first stage model relies on Roberta transformer and CNN to predict the start and end token index of sentiment in the wordpiece token sequence of tweet. The second stage model is based on character_level embeddings and CNN to futhur compute the start and end index of sentiment.The implementation of the second stage model significantly impoved the [jaccard score](https://en.wikipedia.org/wiki/Jaccard_index) from 7.13 to 7.26.

