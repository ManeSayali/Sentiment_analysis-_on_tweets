
# Sentiment Analysis on Tweets using Naive Bayes
This project demonstrates sentiment analysis on tweets using a custom implementation of the Naive Bayes classifier. Instead of using the NaiveBayesClassifier provided by the NLTK library, we have implemented a mathematical Naive Bayes prediction function from scratch.

### Overview
Sentiment analysis is the process of determining the sentiment or emotional tone of a given text. In this project, we focus on classifying tweets as either positive, negative, or neutral based on the text content. We use the Naive Bayes classifier, a probabilistic algorithm, to predict the sentiment of each tweet.

### Features
* Sentiment prediction on tweets using a custom implementation of the Naive Bayes classifier.
* Data preprocessing to tokenize and clean the tweets for analysis.
* Calculation of probabilities and classification based on the Naive Bayes formula.
* Evaluation of the classifier's accuracy using a test dataset.

### Custom Naive Bayes Implementation
Instead of relying on the NaiveBayesClassifier from the NLTK library, we have implemented the core Naive Bayes prediction function ourselves. This function calculates probabilities and performs classification based on the Naive Bayes formula.


Naive Bayes Algorithm
The Naive Bayes algorithm is a probabilistic classification algorithm widely used in natural language processing tasks like sentiment analysis. It's based on Bayes' theorem and makes the "naive" assumption that features are independent of each other given the class label.
Mathematically, the Naive Bayes classifier calculates the probability that a document belongs to a particular class (e.g., positive or negative sentiment) using the following formula:


P(C∣D)= P(C)⋅P(D∣C) / P(D)
​


### Acknowledgments
This project is inspired by the concept of sentiment analysis and the Naive Bayes classifier. It showcases the application of probabilistic algorithms in natural language processing tasks.


