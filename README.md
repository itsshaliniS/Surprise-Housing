# Surprise Housing
>A US-based housing company named Surprise Housing has decided to enter the Australian market. We are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns.
 
## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)



## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.The company is looking at prospective properties to buy to enter the market.
- We are trying to know which variables are significant in predicting the price of a house, and how well those variables describe the price of a house.
- The company has collected a data set from the sale of houses in Australia. 



## Conclusions
- Features are highly skew and correleated
- The best parameter for ridge come out to be alpha =  6 and for lasso alpha = 0.0001
- The r-square of train and test of ridge is 0.9176 and 0.8709 while for lasso is 0.9239 and 0.8733
- Here lasso shows better result than ridge so we are considering lasso
- Variables significant in predicting the house price are :- 
"GrLivArea","OverallQual_9","GarageArea","FullBath","3SsnPorch","TotRmsAbvGrd","Neighborhood_Crawfor","Neighborhood_StoneBr", "MSZoning_FV", "HalfBath"

## Technologies Used
- Pandas - version 1.3.3
- Numpy - version 1.24.4
- seaborn - version 0.12.2
- matplot.pyplot
- sklearn
- Ridge
- Lasso


## Contact
Created by [@itsshaliniS] - feel free to contact me!
