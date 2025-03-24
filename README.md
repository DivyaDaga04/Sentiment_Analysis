# Sentiment_Analysis
# Project Description
Movie review sentiment analysis is a project which is based on natural language processing, where we use NLP techniques to extract useful words of each review and based on these words we can use binary classification to predict the movie sentiment if it's positive or negative.

# Prerequisites
This is the list of required packages and modules for the project to be installed :

Python 3.x ||
Pandas ||
Numpy ||
Scikit-learn ||
NLTK

# The Dataset
Human activities dataset contains about 50000 record which is a sample of movie reviews and a target column "sentiment" which describes the sentiment of the viewer about the movie whether it is positive or negative.

In this part we will see the project code divided to sections as follows:

Section 1 | Data Preprocessing :
In this section we aim to do some operations on the dataset before training the model on it,
processes like :

Loading the dataset
Encoding ouput to binary (Positive : 1 , Negative : 0)
Data cleaning : Remove HTML tags
Data cleaning : Remove special characters
Data cleaning : Convert everything to lowercase
Data cleaning : Remove stopwords
Data cleaning : Stemming

Section 2 | Model Creation :
The dataset is ready for training, so we create a Naive Bayes model using scikit-learn and then fit it to the data.

Section 3 | Model Evaluation :
Finally we evaluate the model by getting accuracy, classification report and confusion matrix.

