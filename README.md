# NLP_Project

This is a NLP Disaster tweet classification project.
This dataset consist of 7613 rows of data and 2 columns.

This project starts with basic analysis of text data then data preprocessing has been performed which includes 'html' tag removal, removing numerical characters, removing stopwords, lemmatizing the words and converting sentences to word by word tokenizer.

Later, words are converted into vectors by using CountVectorizer and TfidfVectorizer both and then data has been splitted into train and test data.
After wards various algorithms has been trained on the dataset which include 'Support vector machine', 'GaussianNB', etc.

Finally atlost 79% accuracy has been achieved by 'Naive bayes' algorithm.
