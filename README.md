# text_sentiment_classification
A small project on sentiment classification of passenger's tweets

Dataset [Twitter US Airline Sentiment](https://www.kaggle.com/crowdflower/twitter-airline-sentiment)

Which was tried:
- SVM over TF-IDF as baseline (f1_score: macro 0.7271, micro 0.7987)
- [Flair](https://github.com/zalandoresearch/flair) model (f1_score: macro 0.7374, micro 0.7947)
- ULMFIT (f1_score: macro 0.7454, micro 0.8139)
- BERT (f1_score: macro 0.7830, micro 0.8323)
- [Universal Sentence Encoder](https://ai.googleblog.com/2019/07/multilingual-universal-sentence-encoder.html) (f1_score: macro 0.7835, micro 0.8357)

