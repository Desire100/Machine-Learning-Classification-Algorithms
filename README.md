# Classifiaction-models
This repository contains different classification models such as Logistic_Regression, K-Nearest Neighbors, Support_Vestor_Machine (SVM), Kernel SVM and Naive_Bayes.

1. Logistic_regression is simply defined as a linear classifier.

2. K-NN: here are the steps on how to implemnet this model.  choose the number of K of neighbors, take the K nearest neighbors of the new data point according to the Euclidean diatance, Among these K neighbors count the number of daa points in each category and then assign the new data point to the category where yoiu counted the most neighbors.

the datasets are provided in .csv file. the description of each datasedt and the task to perfom are given below.

1. Social_Network_Ads: this dataset contains information of users in the social network; Identinty number, Gender, Age and estimated salary. this social network has different business clients which can put their ads on the social  network and one of their clients is a car company who just launched their brand new luxury for a ridiculous price. the task is to see ehich of these users of social network are going to buy this brand new SUV. and so the last column of our dataset tells if YES/NO the use bought this SUV. we are going to buiuld a model to predict if a user is going to bbuy or not the SUV based of two variables which are going to be the age and the estimated salaty.
Our matrix of featyres is only going to be these two columns. we want to find some correllations between the age and the estimated salary of a user and his deecision to purchase YES/NO tp purchase the SUV.
