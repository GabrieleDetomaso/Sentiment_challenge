# Sentiment_challenge
Sentiment analysis project in python that aims to classify the sentiment of Github and Stake Overflow issues.

# Repository structure
There are several python notebooks, the number define the execution order  

Folders:
- **Array_After_Preprocessing** contains the csv files after preprocessing.
  - X_... obtained from 'train.csv'
  - X_TP_... obtained from 'test_public.csv'
- **Datasets** contains
  - **train.csv**, the Train dataset.
  - **test_public.csv**, the unlabeled Test dataset.
  - **test.csv**, and the full Test dataset.
- **Embedding_model_trained** contains the trained model tok2vec to do text embedding.
- **Submission** contains the sentiment predictions for each text in 'test_public.csv'.
- **Utils** contains some custom methods used in notebooks.
