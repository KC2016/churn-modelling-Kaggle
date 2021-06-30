
![kaggle](images/kaggle.png)

# churn-modelling-Kaggle (IN DEVELOPMENT)
Analysis of churns from a bank using dataset [Kaggle](https://www.kaggle.com/shrutimechlearn/churn-modelling)

### Content
This data set contains details of a bank's customers and the target variable is a binary variable reflecting the fact whether the customer left the bank (closed his account) or he continues to be a customer.

## Tools
- Python
- Jupyter Notebook

## What is Churn?

*Churn is a metric that indicates how much your company has lost in revenue or customers. To calculate churn, just divide the number of customers you have lost by the end of the period by the total number of customers you have started. Example: if you lost 10 customers out of 100 = 10% churn rate.* ([reference](https://resultadosdigitais.com.br/blog/o-que-e-churn/))

Therefore, churn is a customer cancellation rate

**% churn = n customer that canceled the service at a month / n of clients in the beginning of the month**

## The problem: Churn

How to avoid churn?

**How to reduce the churn?**
The resasons I can solve with the data I have:
- The customer has no cash flow and can no longer afford the monthly fee for his/her product/service;
- He/she cannot see value in the product/service;
- The customer did not have their expectations met;
- The client has gone bankrupt.

In a nutshell, the customers have no money or the customers don't want the product.


1- identify the best customers and focus on them

- which customers canceled the contract?

- which customer are in risk of cancel the contract?

2- follow the churn daily and identify the reasons

3- deliver properly the product and give a quality service

4- show the customer is important

## Variables:

- RowNumber
- CustomerId
- Surname
- CreditScore
- Geography (country)
- Gender (female, male)
- Age
- Tenure (the time of bond with company)
- Balance
- NumOfProducts (number of products)
- HasCrCard (has credit card)
- IsActiveMember
- EstimatedSalary
- Exited (churn, TARGET)

## EDA - Exploratory Data Analysis

What I consider:

a. customer profile

b. important variables (types, target, distribution, measures)

c. multicolinearity

d. missing values

e. outliers

f. inconsistence

How I explore:

- Distribution of numerical variables.
- Histograms to compare the churn with continuous quantitative variables.
- Counterplots of categorical variables.
- Correlation matrix of numerical variables.
- Confront the target variable with continuous.quantitative variables using boxplots and scatterplots.


## Conclusion

The analysis find the most probable customer profiles to churn, which the bank should to work to retain.