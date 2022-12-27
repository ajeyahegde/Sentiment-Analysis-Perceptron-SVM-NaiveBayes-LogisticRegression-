# Sentiment-Analysis-Perceptron-SVM-NaiveBayes-LogisticRegression

##Sentiment Analysis using Perceptron, Support Vector Machines, Logistic Regression, Naive Bayes algorithms.

###This project includes following steps:

1. Read Amazon Reviews Dataset into Pandas dataframe.
2. Data Cleaning 
- convert the all reviews into the lower case.
- remove the HTML and URLs from the reviews
- remove non-alphabetical characters
- remove extra spaces
- perform contractions on the reviews
3. Data Preprocessing
- remove the stop words
- perform lemmatization
4. Split dataset into train and test dataset.
5. Use TF-IDF for Feature Extraction
6. Train following models using the train dataset
- Support Vector Machine
- Perceptron
- Logistic Regression
- Naive Bayes
7. Predict sentiment ratings for test dataset.
8. Compare accuracy, Precision, Recall and F1-score for each models.
