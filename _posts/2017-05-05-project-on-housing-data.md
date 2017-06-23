---
layout: post
title: Project - Which is the ideal house for you?
categories: [project]
tags: [predictive model, classification]
fullview: true
---

Here in this project I am trying to find out the best features that can predict the price of a house. Here I have divided the project into different parts.
1. To find out the fixed properties that affects the housing price
2. To find how the variable properties can improve the housing price prediction
3. What property characteristics predict an "abnormal" sale?

### Approach

I have a dataset with almost 80 features for each house.This is a dataset that has the details of US house market. First I manually looked into the feature description and differentiated the properties of houses as fixed properties and variable properties. Then did the basic data cleaning where I have avoided the abnormal house sales details for the first 2 parts. Creating meaning full features from already existing ones and dealing with the outliers were part of the project. After data cleaning and Exploratory Data Analysis I went into modelling for each of the problem statement.

### Methods

After finalizing the fixed and variable properties I created dummies variables where required. For the first 2 parts I have used linear regression with Lasso for selecting the best subset of features that could explain the housing price. Third part of the project I have dealt as a classification problem where it predicts whether a sale belongs to abnormal category or not and finds the features from it. I have used logistic regression for modelling and Kbest and recursive feature elimination methods to find the best features.

### Inference

From the first part the 5 best fixed properties that affect the house price are "Total square feet of the plot", "Living Area in square feet", "Neighbourhood", "Age of the house" & "Number of Garage for car park". With the fixed features I was able to predict the house price with 76% accuracy. In the classification model "Sale Type", "Exterior Material", "Basement Quality", "Garage Type" & "MS Zoning" are the 5 best features that shows the abnormal sales. 
Another interesting but obvious finding was the mean sale price of the house increases as the overall quality increases

<img src="https://mahendrashaji.github.io/assets/media/Sale_vs_Qual.png">



<a class="btn btn-default" href="https://github.com/MahendraShaji/Project/tree/master/Housing_Data">click here to check the project on GitHub</a>



