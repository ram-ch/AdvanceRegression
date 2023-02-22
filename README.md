# Advanced House Price Regression
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.




## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The company wants to know:    
* Which variables are significant in predicting the price of a house, and
* How well those variables describe the price of a house.
* Also, determine the optimal value of lambda for ridge and lasso regression.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
The significant variables for the prediction are:   
1. Neighborhood_Crawfor
2. Neighborhood_NoRidge
3. Neighborhood_NridgHt
4. Neighborhood_Somerst
5. Neighborhood_StoneBr
6. Exterior1st_BrkFace
7. BsmtQual_Fa
8. BsmtExposure_Gd
9. BsmtExposure_NA
10. KitchenQual_Fa
11. GarageType_Basment
12. PoolQC_Gd
13. MSSubClass_120
14. MSSubClass_160
15. LotArea
16. MasVnrArea
17. Fireplaces
18. WoodDeckSF

The optimal values of alpha 
for Ridge regression - alpha : 0.01
for Lasso regression - alpha : 0.0001  

Lasso regression is a more robust and regularisable model. 


## Technologies Used
* numpy - version 1.23.5
* pandas - version 1.5.2
* matplotlib - version 3.2.2
* seaborn - version 0.10.1
* statsmodel - version 0.13.5
* scikit-learn - version 1.0.2


## Contact
Created by [@ram-ch] - feel free to contact me!
