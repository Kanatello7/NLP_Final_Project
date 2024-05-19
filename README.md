# NLP_Final_Project
## Sarcasm detection with Logistic Regression and LTSM with Pytorch
This project implements a sarcasm detection model using both Long Short-Term Memory (LSTM) networks and Logistic Regression. The models are trained on the Sarcasm Headlines Dataset from Kaggle to classify headlines as sarcastic or non-sarcastic.

Features
Data Preprocessing: Text data is preprocessed using SpaCy for tokenization, lemmatization, and stopword removal.

Word Embeddings: Text is converted to numerical representations using word embeddings for the LSTM model and CountVectorizer for the Logistic Regression model.

LSTM Model: An LSTM network is employed to capture temporal dependencies in the text data.

Logistic Regression: A baseline model is implemented using logistic regression.

PyTorch Implementation: The LSTM model is built and trained using PyTorch, leveraging its powerful neural network capabilities.

Evaluation: The models' performance is evaluated using accuracy metrics on a test set.

Dataset
The Sarcasm Headlines Dataset is sourced from Kaggle and contains headlines labeled as sarcastic or non-sarcastic. The dataset is preprocessed to remove stopwords and lemmatize words.
