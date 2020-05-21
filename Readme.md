Star Rating Prediction with User Reviews with Yelp Dataset

Introduction
-Yelp was found in 2004 to help people find services like restaurants, dentists, hair
stylists, mechanics, etc,.
-It is use to describe a customers experience in the name of a review so that other users can sort the best business based on the review and rating given.
-Users are allowed to give ratings on a scale of 1 to 5.

Dataset
Gathered json files that are found on the yelp data website. Yelp has curated a well-structured json format files which are fully valid. The dataset has
6,685,900 reviews.
’review_id’: (encrypted review id),

’user_id’: (encrypted user id),

’business_id’: (encrypted business
id),

’stars’: (star rating),

’date’: (date, format
’2019-10-28’),

’text’: (review text),

’votes’: (vote type if it is useful,
funny or cool, count)

Whole of reviews data consists of
5261668 rows and 9 columns.

Models Used:
4 different models were used 

-Naïve Bayes with BOW Vectorizer
-Logistic Regression with BOW Vectorizer
-Logistic Regression with Word2Vec
-Linear-SVC with BOW Vectorizer
-AdaBoost classifier With word2vec
-Keras with LSTM and GRU