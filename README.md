# Hamilton Loans  
To Loan or Not to Loan, That is the Question

![alt text](https://github.com/blizzardfun/HamiltonLoans/blob/master/images/House.jpg)



[Project hosted on Tableau](https://public.tableau.com/profile/linda.reber#!/vizhome/Loans_22/Presentation?publish=yes)

Goal:
The goal of this project was to examine Home Mortgage Disclosure Act (HMDA) data and determine the variables most significant in deciding if a loan is approved or denied. We did not have the most significant credit data available so our results were limited. We went on to compare the various Machine Learning models for effectiveness.

[Data Source]( https://ffiec.cfpb.gov/data-publication/modified-lar) 

[Data Description] (https://github.com/cfpb/hmda-platform/blob/master/docs/v1/2017_Modified_LAR_Spec.csv)

We selected 2017 data from 6 lending institutions(3 banks and 3 online lenders): U.S. Bank, Wells Fargo Bank, Bell Bank, Quicken Loans, American Mortgage & Equity Consultants Inc. (AMEC) and Guaranteed Rate

Data Elements Used:"respondent id","agency code","property type","loan purpose","loan amount","applicant race 1","sex","lien status","loan type modified"

Data Elements Created:
"action modified": Action Taken options reduced to approved and denied  1,2,3,7,8 => approved 4,5,6 => denied,
"income cleaned" : removed null values,
"income loan ratio": income/loan amount

Note: This project is written in Python 3 using Sci-Kit Learn machine learning models (Linear Regression, Logistic Regression, Random Forest, Support Vector Machine (SVM) and Neural Networks) and is visualized on Tableau. 
