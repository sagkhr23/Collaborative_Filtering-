# Collaborative_Filtering-
Recommender System 

A small Recommander system which can predict the value of a movie rating according to the user whose data is given.

I have used collaborative filtering as a special case of  multi target prediction as defined in the reference document file.

I have used ml100k dataset from movie lens from https://grouplens.org/datasets/movielens/ and using its u.data file in which user id along with movie id and rating are given.

In collaborative filtering there is a similarity measure which is defined as
 
For predicting rating of a movie by user u ,we calculate normalized weighted sum of all other user ratings given by 
 
 After seeing MSE for User based collaborative filtering and Item based collaborative filtering, the values are 8.41 and 11.55 , and hence user based collaborative filtering is better.




