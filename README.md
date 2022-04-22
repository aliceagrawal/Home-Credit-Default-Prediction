# Predicting Home Credit Default

### Author - Alice Agrawal

[LinkedIn](https://www.linkedin.com/in/alice-agrawal-7a3194110/) |
[GitHub](https://github.com/aliceagrawal) |
[Email](mailto:alice.agrawal30@gmail.com)


## Overview
![img](Images/5Cs)

The model built in this project is used to predict the default of house credit.

## Problem
I am hired to create a model to improve Wells Fargo’s Home Credit portfolio performance going forward. Wells Fargo wants to predicts whether the client will default using the data provided by the client in its loan application.

## Data

I used a Kaggel competition data which has about 48 thousand entries and 120 features.
The dataset was sourced from: [https://www.kaggle.com/datasets/julianocosta/home-credit](https://www.kaggle.com/datasets/julianocosta/home-credit)


## Methods
A variety of different data science techniques were used to improve estimation.

I started off with a Dummy Classifier to help establish a baseline to compare all future models against. After this I tried a variety of different algorithms hypertuning them where I felt necessary. The specific methods used are:

- Logistic Regression
- Random Forest 
- ADA boosting
- Gradient Boosting

I also employed SMOTE on a few hypertuned parameters to help with the class imbalance.

## Results

After the iterative process, our final model is Random Forest with parameter tuning and the result is:
<br />
[Results:](Images/Results.png)

## Conclusion
Three recommendations:
1. Wells Fargo should aim to increase the number of revolving loans as the default on these are much lower. 
2. Wells Fargo should target clients older than the age of 40 years. 
3. Clients with employment type of working, businessmen and students should be focused on to improve their default rates.

## Next Steps
To further improve the model, in the future I could look into:
1. Stacking the the different models to improve the model further. 
2. Collecting more recent data
3. Including sentiment analysis using the worded answers in the application. 

## Repository Structure
```
├── Data/home-credit-default-risk
│     ├── HomeCredit_columns_description.csv
│     └── application_train.csv.zip
│ 
├── Images
│     ├── Age.png
│     ├── Employment.png
│     ├── EmploymentYrs.png
│     ├── Gender.png
│     ├── Income.png
│     ├── LoanType.png
│     ├── home_credit_data.png
│     ├── 
│     ├── 
│     └── 
│    
├── README.md
│ 
├── Final_notebook.ipynb
│
├── Slides
│ 
└── .gitignore
```
