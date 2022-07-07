# Fake-news-detection-TfidfVectorizer
OBJECTIVE:
The main objective is to detect the fake news, which is a classic text classification problem with a straight forward proposition. It is needed to build a model that can differentiate between “Real” news and “Fake” news.

REQUIREMENTS:
Python

Numpy

Pandas

TfidfVectorizer

PassiveClassifier

Sklearn



Data:
I have shared my training data in the below link.

https://drive.google.com/file/d/1RlIfucizysBxCs0w3hohQWgsWaGd21iL/view?usp=sharing
Processed Method:
First,I have imported the required modules to the colab file.I have inserted the dataset to a variable using pandas.read_csv() function

Next, I have applied the Data preprocessing methods to the training dataset.I have filled all the null values present in the dataset with blank space''.

I have created a column named 'content' in the dataframe which consists of both 'author' and 'title' column values.

Next, I have seperated the features and label and assigned them to variables.

Using ,TfidfVectorizer we removed the stopwords and using the PassiveAggressiveClassifier we fit the model and we calculated the accuracy I created a function which will return all the text data consisting of only root words.Then, lets take the feature as column 'content' and apply the vectorizer function to convert text data into numerical data.

Now, lets split the training data amd testing data using train_test_split() function.Then, I used Logistic Regression to create the model.I finally achieved accuracy score of the training data as 96.9% and for testing data as 95.2%



Refrences:
https://www.youtube.com/watch?v=nacLBdyG6jE



https://www.pantechsolutions.net/fake-news-detection-using-machine-learning
