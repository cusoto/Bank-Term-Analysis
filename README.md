# Bank-Term-Analysis
Exploratory data analysis and binary classification of bank term candidates.  

## Summary
The goal for this project is to explore which attributes most influece a bank term subscription,
then create a Classification Model to predict whether a client will subscribe to a bank term.

## Bank Marketing Data

We will be using the Bank Marketing dataset from the UCI Machine Learning Repository ([link here](https://archive.ics.uci.edu/dataset/222/bank+marketing)). The data was obtained from marketing campaigns of a Portuguese banking institution.

There are 21 columns in the data:
1. **age**
2. **job**: type of job
3. **marital**: marital status
4. **education**: highest form of education
5. **default**: has credit in default
6. **housing**: has housing loan
7. **loan**: has personal loan
8. **contact**: contact communication type
9. **month**: month of contact
10. **day_of_week**: week of contact
11. **duration**: duration length of contact 
12. **campaign**: number of contacts performed during this dataset campaign
13. **pdays**: number of days since last contact
14. **previous**: number of contacts performed before this dataset campaign
15. **poutcome**: outcome of previous marketing campaign
16. **emp.var.rate**: employment variation rate, measuring changes in employment in labor market
17. **cons.price.idx**: consumer price index, measuring changes in average price levels
18. **cons.conf.idx**: consumer confidence index, measuring consumer confidence in overall state of the economy
19. **euribor3m**: euribor 3 month rate, measuring average interest rate that banks are willing to lend for unsecure funds
20. **nr.employed**: number of employees in labor market
21. **y**: did the client subscribe a term deposit

All missing data has the value of "unknown".

## Procedures

The steps taken for this project are as follows:

1. Exploratory Data Analysis
    - Numerical Attributes and Correlations
    - Categorical Attributes and Data Visualizations

2. Data Cleaning & Preparation
    - Removing Duplicates
    - Handling Missing Data
    - Converting Categorical Figures
    - Balancing the Dataset

3. Classification Model
    - Splitting into Train & Test sets
    - Scaling Data
    - Training the Model
    - Evaluating the Model

## Citation

[Moro et al., 2014] S. Moro, P. Cortez and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, In press, http://dx.doi.org/10.1016/j.dss.2014.03.001