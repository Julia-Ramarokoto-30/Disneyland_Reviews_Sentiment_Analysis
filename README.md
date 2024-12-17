# Disneyland_Reviews_Insights

![alt text](
https://cdn.wallpapersafari.com/13/95/hdRfnU.jpg)

### Subject

"The goal of this project is to classify Disneyland customer reviews into positive, neutral, or negative categories."
We will use the csv format dataset Disneyland Reviews from Kaggle avaiaible here : https://www.kaggle.com/datasets/arushchillar/disneyland-reviews?resource=download

### Methodolody

Because we want to classifiy each reviews in a particular sentiment class, we will use a Logistic Regression model which is a type of supervised learning.

### Preprocessing

Since the dataset doesn't originally contain a target value, we will create it manually.
We are gonna perform some nlp tasks , like lemmatization, removing the stop words etc...

### Model training
In other for the features to be understood by the model, we have to convert the words into numerical values using a TFIDF vectorizer

