# SMS-Classification
It is a python model to categorize sms as a spam or not spam

# Dataset
The dataset used is the open source dataset provided by UCI machine learning repository.
https://archive.ics.uci.edu/ml/datasets/sms+spam+collection

# Preprocessing
The data is read by pandas and then we use nltk library to do the preprocessing and build the corpus.
First the nonalphabetic characters are removeed from the sms, then they are converted to smaller case and are separated based on the space. Now the stopwords are removed from the sms and the words left are converted to the basic word from which it originated.

# Model
It is implementation of Naive Bayes Gaussian classifier to classify sms as spam or not spam.
It uses other basic libraries like pandas,numpy,nltk.
The basic model has very good confusion matrix scores on real data.
