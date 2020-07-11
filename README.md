# Movie Recommendation System

This program predicts rating of the movies (the program uses SVD algorithm to predict movie ratings) and then recommend movies based on these prediction to the uers. 

## Description
The project creates a movie recommendation system based on the technique of Colloborative filtering. To implement Colloborative filtering, SVD which is on eof the algorithms of Matrix Factorization is used. Matrix factorization algorithms work by decomposing the user-item interaction matrix into the product of two lower dimensionality rectangular matrices.We start by implementing matrix factorization using Singular Value Decomposition. Scikit learn library was used for theimplementation of this algorithm.The attributes considered were movieId, userid and ratings. 5 fold cross validation technique is use for validation purposes. 

## Dataset 
The dataset was taken from this(https://grouplens.org/datasets/movielens/) link. The particular file we have used consists of 3 columns namely movieid, userid, and rating.

## Machine Learning Algortihtm Used
- Matrix Factorization
  - Singular Value Decomposition (SVD)
## Important Libraries 
- sklearn
- surprise
