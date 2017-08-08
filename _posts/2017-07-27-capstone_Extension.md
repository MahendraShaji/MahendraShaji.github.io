---
layout: post
title: Capstone-Extension Project- Sales prediction for chain of stores
categories: [project]
tags: [capstone, project, prediction]
comments: true
fullview: false
---

In the 1st part of the Capstone project I have created a predictive model that predicts the weekly sales of 45 stores for next 3 months. In the first part I haven't considered the department level data and took the sum of department sales to find the total sales of each store.

In this part of the project I am extending the scope to department Level and trying to predict the sales of all the 98 departments for each store. Since my system couldn't handle this massive amount of data I am selecting the first 5 stores data to implement the same. This is because by selecting the first 5 stores it would be a perfect prototype of the entire data.



### Objective

 Part1. Create a predictive model that predicts the weekly sales of 45
       Stores (In this stage I am not planning to predict the sales on 
	 Department Level)

    *Part2. Extend the project to Department Level (Future Work)*
    
### Method

	Here I have concentrated on part2 of the project. I have scaled down and took data of 5 stores which works exactly as a prototype for big data models. I have done feature engineering and created new feature from the existing features. The new feature is a combination of Store number and Department number. This is because while we convert to dummy variable the combination will have more explaining power on the data trends. 

In this extension I haven't considered the economic features or any other features. This is an attempt to predict the 3 months sales by considering timeline as another feature with the newly created.

 
### Conclusion

 I have come up with the models that  predict the weekly sales of 98 departments in 5 stores with around 90% of accuracy for 3 months(90 Days). This have further scope to expand and check how it worked for each store or for each department. That would be the future development plans.

#### Check this in GitHub

<a class="btn btn-default" href="https://github.com/MahendraShaji/Capstone">click here to check my capstone</a>

