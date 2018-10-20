# 20_NEWSGROUPS

This data set consists of 20000 messages taken from 20 newsgroups, i.e. One thousand Usenet articles from each of the 20 newsgroups. The dataset can be found in the sklearn.datasets or can be downloaded from: 
https://archive.ics.uci.edu/ml/machine-learning-databases/20newsgroups-mld/20newsgroups.data.html

The codes in this project learn to predict the correct newsgroup an article belongs to after it has been trained using Naive-Bayes Classifier. There are 2 different methodologies used to achieve the same thing:
<br>
**Method 1** Data has been preprocessed and the naive-bayes algorithm has been coded. The algorithm used is an implementation of the one given in 'table 6.2' of the book 'Machine Learning by tom Mitchell' 
<lr>
**Method 2** Data has been vectorised using Count Vectoriser and Tfidf Vectoriser. After that sklearn classifiers have been used. 

