# Loan-Eligibility-Prediction
How can Banks and Non Banking Financial Companies predict Loan Eligibility of a borrower

When a customer applies for a loan at a company, the company determines whether to grant or reject the loan based on the likelihood of the loan being repaid by the borrower. The factors involved in determining this likelihood are complex and extensive statistical analysis and modelling is required to predict the outcome for each individual case. The attempt here is to build and implement a Machine Learning solution than can predict if a loan should be granted to the borrower based on the historical data provided.

The dataset contains 111107 rows and 19 columns. of which 22197 records are duplicate and have been removed.

The below columns in the dataset have missing values, these will be dealt with during EDA and Data Preprocessing.

|# Variable Name            |     % |
--------------------------------------
|Tax Liens                   |    0.0001
|Bankruptcies                |    0.0022
|Years in current job        |    0.0429
|Credit Score                |    0.2400
|Annual Income               |    0.2400
|Months since last delinquent|    0.5456

The below graph shows the distribution of the target variable "Loan Status". There were 63737 where loans were give and 25173 instances where loans were Refused. 

![](Images/Loanstatus.png)

# Exploratory Data Analysis and Data Preprocessing
