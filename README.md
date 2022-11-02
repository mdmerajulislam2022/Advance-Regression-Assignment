# Project Name : Advance Regression Assignment Part I & II
 
Problem Statement
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

The company is looking at prospective properties to buy to enter the market. We are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

The solution is divided into the following sections:

Data understanding and exploration
Data cleaning
Data preparation
Model building and evaluation
Business Goal
We are required to model the price of houses with the available independent variables. 
This model will then be used by the management to understand how exactly the prices vary with the variables. 
They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. 
Further, the model will be a good way for management to understand the pricing dynamics of a new market.

#### Project Version : V1
#### Project Status  : Completed
#### Release Data    : 02/11/2022

### Files: 
* .pynb file -- jupyter file containing the code
* .pdf file -- power point  in PDF format
* .csv file --- containing original data (1 csv and 1 xlsx file)

### Libraries Used :
* Pandas : 1.2.3
* numpy : 1.20.3
* matplotlib: 3.5.2
* seaborn : 0.11.2
* sklearn

#### Analysis and Findings :
cnt = 0.199434 + 0.490988 X temp + 0.233570 X yr + 0.081741 X season_Winter + 0.076846 X mnth_Sep + 0.046487 X season_summer - 0.052057 X mnth_Jul - 0.067169 X season_ Spring - 0.080167 X weathersit_Mist & Cloudy - 0.097463 X holiday - 0.147919 X windspeed - 0.284199 X weathersit_Light Snow & Rain


Conclusion :
we got a decent score for both Ridge and Lasso regression.
Ridge : Train :92.88 Test :91.56
Lasso : Train :91.9 Test :91.70
As per the problem statement The company wants to know:
Which variables are significant in predicting the price of a house

How well those variables describe the price of a house.

In the below segment we have given the features that are significant and impacts the price of a house

Top 10 most significant variables in Ridge are:
Variables with positive coefficient

MSZoning_RL 0.30219
OverallQual 0.2085
MSZoning_FV 0.20233
MSZoning_RM 0.19709
Variables with negative coefficient

RoofStyle_Gable: -0.05179
KitchenAbvGr: -0.06137
Exterior1st_Wd Sdng: -0.06149
Condition2_PosN: -0.08819
YearBuilt: -0.12026
Top 10 most significant variables in Lasso are:
Variables with positive coefficient

GrLivArea 0.29664
OverallQual 0.23678
GarageCars 0.10639
OverallCond 0.10597
BsmtFinSF1 0.09307
Variables with negative coefficient

Functional_Maj2: -0.02496
MSSubClass_2-STORY PUD - 1946 & NEWER: -0.04199
KitchenAbvGr: -0.04609
Condition2_PosN: -0.08236
YearBuilt: -0.1235
These Varaiables are directly proportional to each other.
Optimal Value of lamda for ridge : 10
Optimal Value of lamda for Lasso : 0.0001



<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements 
 - Upgrad/IITB
 - Online Sources : Stackoverflow, Pandas , seaborn , plotly, numpy , matplotlib,sklearn
