# Recommendations-with-IBM
Analyzed the interactions that users have with articles on the IBM Watson Studio platform, and made recommendations to them 


## Introduction
For this project I analyzed user interactions of articles on the IBM Watson Studio platform, and used code to make recommendations for them about new articles that they will like. 
Below you can see an example of what the dashboard could look like displaying articles on the IBM Watson Platform.


## Project Tasks

#### I. Exploratory Data Analysis
* - get a better understanding of the data and explore it with answering a few questions
#### II. Rank Based Recommendations
* -	find the most popular articles simply based on the most interactions
#### III. User-User Based Collaborative Filtering
* -	clean the data for a matrix
* -	look at users that are similar in terms of the items they have interacted with
* -	provide recommendations for new users
#### IV. Content Based Recommendations (EXTRA - NOT REQUIRED)
* - use rake_nltk to sort for key words in articles and use cosine similarity to find relevance across users
#### V. Matrix Factorization
* - use machine learning and SVD approach to building recommendations
* - perform assessment of the predicted vs. the actual values
* - analyze the built recommendation system 

## Project Files
* Recommendations_with_IBM.ipynb - notebook code analysis
* Recommendations_with_IBM.html - same notebook file but in html
* articles_community.csv, user-item-interactions.csv - raw data in a csv format
* not included in github - user_item_matrix.p, project_tests.py, top_10.p, top_20.p, top_5.p

## Added Installation
* install rake-nltk package for nltk in part IV
* other: pandas, numpy, matplotlib, project_tests, pickle, itertools, sklearn, nltk
