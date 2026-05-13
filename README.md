Spam Email Classifier using Classical NLP

This project is a Natural Language Processing (NLP) based spam email classification system built using Python and Scikit-learn.


The project demonstrates:

Text preprocessing
Feature engineering
TF-IDF vectorization
Machine learning model comparison
Spam classification using NLP techniques

Problem Statement

The goal of this project is to classify emails as:

Spam
Not Spam (Ham)

using machine learning and NLP techniques.


Dataset Features

The dataset contains:

Email subject
Email body text
Word count
Character count
Sentence count
Spam related indicators

NLP Preprocessing Steps

The following preprocessing steps were performed:

Lowercasing
Tokenization
Removing special characters
Stopword removal
Stemming


TF-IDF Vectorization

TF-IDF Vectorization was used to convert textual data into numerical feature vectors for machine learning models.


Models Tested

The following models were tested:

K-Nearest Neighbors
Gaussian Naive Bayes
Multinomial Naive Bayes
Bernoulli Naive Bayes
Logistic Regression
Decision Tree
Random Forest
AdaBoost
Bagging Classifier
Extra Trees Classifier


Final Model

Multinomial Naive Bayes was selected as the final model because it is well-suited for sparse TF-IDF based text classification problems.

Several models achieved near-perfect performance on the dataset.


Model	Accuracy
KNN	99.65%
MultinomialNB	100%
Logistic Regression	100%
Random Forest	100%

mportant Observation

The dataset appeared highly separable, resulting in extremely high performance across multiple machine learning models.

This suggests that the dataset is significantly cleaner and less noisy than typical real-world spam classification datasets.


Therefore, while the project demonstrates a complete NLP workflow, the model performance may not fully represent real-world spam detection complexity.



Technologies Used

Python
Pandas
NumPy
Scikit-learn
NLTK
Matplotlib
Seaborn


Learning Outcomes

This project helped in understanding:

NLP preprocessing pipeline
TF-IDF vectorization
Text classification
Feature engineering
Model evaluation
Dataset separability and limitations




