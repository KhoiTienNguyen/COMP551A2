# COMP551A2
In this project, we were tasked to implement Naive Bayes
classification and Softmax Regression models to classify
the following datasets: 20newsgroups and Sentiment140.
The 20newsgroups dataset consists of over 18000 newsgroup posts over 20 topics and Sentiment140 dataset consists of a collection of tweets with a positive, negative sentiment. Our goal was to find the model with the highest accuracy. We trained our Gaussian Naive Bayes model, Multinomial Naive Bayes model and SciKit learn’s Logistic Regression model using different hyper-parameter settings for each
of the classifiers, which we found to influence the results.
We implemented k-fold cross validation on every model
to ensure performance consistency. We found that our best
performing model was the Logistic Regression model on
20newsgroup, which reported an accuracy score of 72.28%
on the final test set with tuned Hyper-parameters(C=100,
Solver = liblinear). On Sentiment140 dataset, our Multinomial Naive Bayes model using tfidf was our best performing
model with a score of 76.88% on the final test set. Overall, Softmax Regression was significantly faster to train over
both datasets.

Authors: Chloe Mills, Shania Wan-Bok-Nale, Khoi Nguyen
