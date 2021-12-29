# Project Name
> Lending Club Case Study.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The current exercise is part of UpGrad's "Introduction into Statistics" course assignment.
- The goal of the exercise is to help the Lender to make better credit decisions (rejection or approval of the credit application) by identifying factors that can serve as signals for potential future credit defaults. 
- The current analysis is based on two files:
* 'loan.csv' - historical portfolio data containing records of approved credit contracts (both defaulted and non defaulted). Data about rejected loan applications is not available.
* 'Data_Dictionary.xlsx' - dictionary describing the business content of the attributes within the loan.csv?

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Customer financials: The 'Annual income' of the customer is in negative correlation with the default ratio meaning the higher the income bucket, the lower the default ratio is. The Debt To Income ratio is in positive correlation with the default ratio meaning the higher the DTI the higher the default ratio is. These observations are matching the intuitions.
Loan information: The Loan Amount is in positive correlation with the default ratio The Purpose of the loan can be a good indication. SME loans tend to have higher default ratio The Term of the loan is a good indication as well. The longer (60 months) category has higher default ratio These attributes however are also correlated!
Other factors: Loans with Mortgage are less likely to go default. The same applies for Car loans. It indicates that people who have something to lose (Car or Home) tend to be more careful with decision on loan payments.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Exploratory Data Analysis
- Python 3
- Pandas, Numpy, Matplotlib, Seaborn, Datetime

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

<!-- ## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com). -->


## Contact
Created by [@nanaiz] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->