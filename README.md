# Emily's NLP Blog
## [Book Recommender](https://github.com/EmilyNLP/Book-Recommender)
**Key words: Web Scraping, Popularity Ranking, Naive Bayes, SVM, TF-iDF, Content_based, Collaborative filtering**

Part1.[Web Scraping and EDA](https://github.com/EmilyNLP/Book-Recommender/blob/master/1_Web%20Scraping_EDA.ipynb) <br/>
Part2.[Weighted Rating__Naive Bayes__SVM](https://github.com/EmilyNLP/Book-Recommender/blob/master/2_Weighted%20Rating_Naive%20Bayes_SVM.ipynb) <br/>
Part3.[Content Based Recommender](https://github.com/EmilyNLP/Book-Recommender/blob/master/3_Content%20Based%20Recommender.ipynb)  <br/>
Part4.[Collaborative Filtering with neighborhood methods](https://github.com/EmilyNLP/Book-Recommender/blob/master/4_Collaborative%20Filtering%20with%20neighborhood%20methods.ipynb)  <br/>
Part5.[Collaborative filtering with latent factor models](https://github.com/EmilyNLP/Book-Recommender/blob/master/5_Collaborative%20filtering%20with%20latent%20factor%20models.ipynb)  <br/>


## [BioMedical Question Answering](https://github.com/EmilyNLP/BioMedical-Question-Answering)
**Key words: BioMedical Question Answering, General to domain-specific transfer learning, SQuAD to BioASQ, RoBERTa**

First, pretrain RoBERTa with BioMedical publication corpus. Next, Fine-tune the RoBERTa QA Model with SQuAD Dataset.Then, Fine-tune the RoBERTa QA Model with BioASQ dataset. The performance of the final model validated on the BioASQ test dataset reaches at 84 for F1 score and 72 for EM(exact match), which is a decent result. 


## [Fine-tune GPT-2 to generate stories](https://github.com/EmilyNLP/Fine-Tune-GPT2-to-Generate-Stories)
**Key words: GPT-2, Generative language modeling, story generate**

Fine-tune GPT-2 with specific domain texts. The fine-tuned model decreases the perplexity for valid dataset from 39 to 24, which is a improvement. Howerver, from human evaluation, the generated stories from plain and fine-tuned models are almost at the same level. That means we still have a long way to explore in the field of generative language modeling. 

## [Two-stage-models to extract tweet sentiment](https://github.com/EmilyNLP/Tweet-Sentiment-Extraction)
**Key words: Roberta&CNN, WordPiece&character hybird embedding, two-stage-models**

The first stage model relies on Roberta transformer and CNN to predict the start and end token index of sentiment in the wordpiece token sequence of tweet. The second stage model is based on character_level embeddings and CNN to futhur compute the start and end index of sentiment.The implementation of the second stage model significantly impoved the [jaccard score](https://en.wikipedia.org/wiki/Jaccard_index) from 7.13 to 7.26.

## [Quora Insincere Question Identification](https://github.com/EmilyNLP/Quora-Insincere-Questions-Classification)
**Key words: Sentiment analysis, LSTM, Attention**

Build and train LSTM model with Attention mechanism to identify Quora insincere questions. Programmed with python and keras. The score ranks in the top of 16% out of 4037 teams.

## [Use news and market state to predict stock trend](https://www.kaggle.com/emily2008/two-sigma-stock-news-market?scriptVersionId=7345306)
**Key words: LightGBM, news&market state**

Build a LightGBM model to predict how stocks will change based on the market state and news articles. The outcome performance ranks in the top  of 4% out of 2927 teams.

## [Is this your favorite food?](https://github.com/EmilyNLP/Identify-Cuisine-Type-with-Recipe)
**Key words: EDA, Multi-labels classifier, Feature Engineering**

First, pre-process the cuisine receipe, then feed them to multiple models, choose the model with the best accuracy to predict the food types. 
