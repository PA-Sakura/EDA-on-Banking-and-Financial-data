# Introduction
This case study aims to give you an idea of applying EDA in a real business scenario. In this case study, apart from applying the techniques that I have learnt, I also developed a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.
Presented the overall approach of the analysis in a presentation. 

# Problem Statement and Business Objectives
This case study aims to identify patterns which indicate if a client has difficulty paying their installments which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. This will ensure that the consumers capable of repaying the loan are not rejected. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.

To develop your understanding of the domain, you are advised to independently research a little about risk analytics - understanding the types of variables and their significance should be enough).

# Data 
Application data - (Data file 1)
Previous Application Data (Data File 2)
Couldn't load the data into github as the size is too big.

Imported libraries and set notebook options, the read the data and first glimpse. 
Checked and cleand data, Checked missing data, performed missing value treatment by imputation and treated outliers. 
As the Application data was imbalanced Divided the dataset into two different datasets based upon 'Target' value.
Performed Univariate analysis and Bivariate analysis, and found the top 10 correlations and merged the Application data.
Performed the same steps for Previous data and finally made the following conclisions. 

# Findings
Application data - (Data file 1)
The clients with maternity leave as their income type seem to have high % of payment difficulties, so they are the driving factors to be avoided
The clients with low skilled laborers as their occupation type have high% of payment difficulties, so they are the driving factors to be avoided
The clients with lower secondary as their education type have higher% of payment difficulties, so they are also one of the driving factors to be avoided
Previous Application Data (Data File 2)
The clients with Refusal to name the goal as their loan purpose have higher % of payment difficulties, so they are also one of the driving factors to be avoided
The clients with Refused loans as their previous contract status also have higher % of payment difficulties, so they are also one of the driving factors to be avoided
The clients with Revolving Loans as their previous contract type also have higher % of payment difficulties, so they are also one of the driving factors to be avoided

# Credible applications
According to data most of the defaulters are working clients, however this is just a correlation but not a causation. Hence proper scrutiny must be done on other parameters before the refusing the application of loan.
In the given data female applicants have more difficulties in count when compared to male applicants but when compared in percentages, they do not make much difference. Hence there should not be any bias based on gender.



