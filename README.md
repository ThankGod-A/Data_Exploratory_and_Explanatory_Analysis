### Prosper Loan Data Exploration
**By ThankGod Agada**

#### Installation
The following libraries were used:
1. Pandas
2. Numpy
3. Matplotlib
4. Seaborn

#### Dataset
The dataset being used for this project is the Prosper loan Dataset, provided by Udacity. The dataset has 113,937 loan records with 81 features or variables. Most of the variables are either numeric or categorical variables.

The dataset can be found [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000), and feature documentation is also available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).

The dataset features or variables contain information mainly about the borrower and attributes associated with the loan itself.

#### Summary of Findings
The main feature of interest for me is the _LoanOriginalAmount_, one of the key features of the borrower. The focus is to explore information relating to borrowers for insights and relationships with respect to the loan they accessed. 

I started my exploration with a univariate analysis by looking at the borrower's monthly income, I discovered that the majority earn between ($)2500k - 7500k. When compared to the other range of monthly income, it can be deduced that they are low-income earners, and the loan amount they mostly took is between 5k - 15k. The duration of the loan known as 'Term' ranges from 12, 36, and 60 months, and a vast majority of the loan accessed had a Term of 36 months. Further investigation revealed loans were issued more in 2013 with a count of over 30k, and January recorded the highest number of borrowers, followed closely by October & December. The distribution for loan payment is unimodal and right skewed. The majority of the borrowers pay at least 200 dollars monthly, and the highest loan payment is 1200k while a majority of the payment ranges between 200 - 400 dollars monthly.

I delved deeper into finding the relationship between pairs of variables most especially my main features and other variables, doing a bivariate analysis. A strong relationship exists between the Monthly Payments and the Loan amount. It suggests the majority of the borrowers are consistent and committed to their payments. Their income range was investigated and the borrowers with the highest IncomeRange ranging between 75k - 100k+ got to access a higher amount of loan. The higher your IncomeRange the higher the loan amount accessed. Furthermore, Borrowers with such an income range are majorly homeowners.

Doing a multivariate exploration revealed that Term (Loan Duration) doesn't significantly impact the relationship between loan original amount and monthly income. 

#### Key Insights for Presentation
Here, I started my presentation by giving an overview of the dataset and the main feature of interest which is Loan Original Amount, and the relationship it has with other variables such as Stated Monthly Income, Monthly Loan Payment, Income range, and how this correlation is affected by other variables. 

Afterward, I proceeded to show these insights and relationships with appropriate visuals followed by my observation or deductions.
