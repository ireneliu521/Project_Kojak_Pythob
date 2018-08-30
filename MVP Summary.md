## MVP Summary
---------

### Domain
The main objective of my passion project is to build a machine learning model to predict customer lifetime value (CLV). CLV can help companies to determine the worth of their business and then attract investers for funding or increase the probability to borrow more money. Especially in the retail industry, getting current customers to purchase more ir more important than acquiring new customers. In this case, CLV can help companies make decisions more precisely.
The other objectives are on sales returns and future sales forecasting. Some concerns will be elaborated in the knowns & unknowns section.


### Data

The Superstore dataset contains 51,290 retail-to-customer transactions made in 2014 - 2015. There are 24 features corresponding to each transaction. 

### Knowns & Unknowns

On Customer lifetime value
Known: Customer lifetime value will be first computed. According to the suggestion from XXXX, I will *set* 3 years for the average customer life span and the information from the dataset will be used to fill in the blank of the equation. 

Unknown:

On return
Known: I am planning to add some demographic data based on the city and country that the customer was located and the time that the order was placed.

Unknown: The dataset is extremely imbalanced in terms of sales return. The number of return records is 1,079 but the number of normal transactions is 50,211. The accuracy score of the model is probably not going to look good even if I perform oversampling on the dataset. How to improve the model performance if I get a bad one will be the problem.

On Sales
Known: Time series analysis will be performed on the dataset to forecast the future sales. 

Unknown: 
