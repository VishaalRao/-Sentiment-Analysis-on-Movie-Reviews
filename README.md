# Sentiment Analysis on Movie Reviews
By Vishaal Rao
Classify the sentiment of sentences from the Rotten Tomatoes data set

# Introduction
The dataset is comprised of tab-separated files with phrases from the Rotten Tomatoes dataset. The train/test split has been preserved for the purposes of benchmarking, but the sentences have been shuffled from their original order. Each Sentence has been parsed into many phrases by the Stanford parser. Each phrase has a PhraseId. Each sentence has a SentenceId. Phrases that are repeated (such as short/common words) are only included once in the data.

Dataset taken from: https://www.kaggle.com/c/sentiment-analysis-on-movie-reviews/data

# Important Libraries used in the following project

NLTK: The Natural Language Toolkit, or more commonly NLTK, is a suite of libraries and programs for symbolic and statistical natural language processing for English written in the Python programming language.

Pandas:pandas is a software library written for the Python programming language for data manipulation and analysis.

sklearn.feature_extraction: text The library has been used to perform Countvectorization.

sklearn.linear_model: The library has been used to perfrom logistic regression on the given data set.

re: A regular expression is a special sequence of characters that helps you match or find other strings or sets of strings, using a specialized syntax held in a pattern.

# Methodology
CountVectorizer provides a simple way to both tokenize a collection of text documents and build a vocabulary of known words, but also to encode new documents using that vocabulary.
Logistic Regression is a statistical model that in its basic form uses a logistic function to model a binary dependent variable.
Naive Bayes classifier: are a family of simple "probabilistic classifiers" based on applying Bayes' theorem with strong (naive) independence assumptions between the features.
Metrics used
Accuracy score: It is simply a ratio of correctly predicted observation to the total observations.

Accuracy = TP+TN/TP+FP+FN+TN

F1-Score: F1 Score is the weighted average of Precision and Recall. Therefore, this score takes both false positives and false negatives into account.

F1 Score = 2(Recall * Precision) / (Recall + Precision)*

Recall=TP/TP+FN

Precision=TP/TP+FP

TP-True Positive, TN-True Negative, FP-False Positive, FN-False Negative
