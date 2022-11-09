# Lending Club Case Study
> This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 
> Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
> If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
> In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 
> To develop your understanding of the domain, you are advised to independently research a little about risk analytics (understanding the types of variables and their significance should be enough).

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Exploratory Data Analysis.
- Loan lending risk management
- Identify a major factor or combination of factors to lend the loan
- Data sets with 39717 instances and  111 attributes 


## Conclusions
- The data set is not have duplicated instances. 
- Fifty-four columns have all missing values.
- The following columns have more number of missing values 
  "desc","mths_since_last_delinq","mths_since_last_record","next_pymnt_d","tot_hi_cred_lim","mths_since_last_major_derog","total_bal_ex_mort","total_bc_limit","total_il_high_credit_limit","member_id","url","emp_title","zip_code","tax_liens"
- 82.96 percent loans were fully paid. 
- 14.16 loans were charged off 2.87on track
- Most of the loans taken for debt consolidation
- Outliers:annual_inc column
- Loan amount, investor amount, and funding amount are strongly correlated.
- Annual income with DTI(Debt-to-income ratio) is negatively correlated.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy
- pandas
- matplotlib
- seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by case study done by VINAY PRATAP SINGH
- This project was based on [kaggle](https://www.kaggle.com/).
- This project was based on [towardsdatascience](https://towardsdatascience.com/end-to-end-case-study-classification-lending-club-data-489f8a1b100a/)


## Contact
Created by [@pavanalina] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
