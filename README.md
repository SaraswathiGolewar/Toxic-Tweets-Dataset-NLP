# Toxic-Tweets-Dataset-NLP
# Problem Statement
The given dataset is a collection of Tweets. All the tweets are labelled as Toxic:1 and Non-Toxic:0. We have to apply the NLP methods and machine learning algorithms on the given  models(BoW and TF-IDF) and produce the metrics to making decisions based on the comprehensive evaluation.

# Libraries Used in Python
1.pandas

2.matplotlib

3.seaborn

4.scikit-learn

5.nltk

# Approach
1.Start by importing all the necessary libraries and reading the toxic traits dataset which can be downloaded using the link https://www.kaggle.com/datasets/ashwiniyer176/toxic-tweets-dataset.

2.Performing EDA so as to convert the tweets in a form which is useful in further processing. This includes changing the test in lowercase, removing puncuations, tokenizing, removing stop words and lemmatizing the words.

3.Using bag of words and TF-IDF vectorization to convert the textual data into numerical features.

4.Splitting the data into training set and testing set.

5.There are five differnt models for the calssfication: Decision Trees, Random Forest, Naive Bayes, K-nn classifier and support vector machine and these are trained using both BOW and TF-IDF features respectively.

6.Precision, F1-score and RoC-AuC are calculated for each model and vectorisation technique combination.

7.Confusion matrices and ROC curves are plotted to evaluate the performance of each model.
