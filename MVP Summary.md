## MVP Summary
---------

### Domain
One of my goals of this passion project is to build a machine learning model to predict customer lifetime value (CLV). CLV can help companies to determine the worth of their business and then attract investers for funding or increase the probability to borrow more money. Especially in the retail industry, getting current customers to purchase more ir more important than acquiring new customers. In this case, CLV can help companies make decisions more precisely.
The two other goals are on sales returns and future sales forecasting. My concerns on predicting the sales returns will be elaborated in the knowns & unknowns section.

### Data

The Superstore dataset contains 51,290 retail-to-customer transactions made in 2012-2015. There are 24 features corresponding to each transaction. Most of them are the information  directly related to the transaction, so I am planning to add more features which is related to the customers such as the gender based on their first name, adding average income of the area where the customers live.

### Knowns & Unknowns

1. On Customer lifetime value <br>
Known: Customer lifetime value will first be computed. I will set 3 years for the average customer life span since it's the information that is hard to measure and the other elements of the CLV formula will be filled in with the inforamtion from the dataset. <br>
Unknown: Since the CLV is calculated using the information in the dataset, my concern is that the model might not be able to predict the value very well.

2. On return <br>
Known: I am planning to add some demographic data based on the city and country that the customer was located and the time that the order was placed. <br>
Unknown: The dataset is extremely imbalanced in terms of sales return. The number of return records is 1,079 but the number of normal transactions is 50,211. The accuracy score of the model is probably not going to look good even if I perform oversampling on the dataset. How to improve the model performance if I get a bad one will be the problem.

3. On Sales <br>
Known: Time series analysis will be performed on the dataset to forecast the future sales. <br>

Unknown: 
