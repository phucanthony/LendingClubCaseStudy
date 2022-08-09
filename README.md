# Lending Club Case Study
> Basic Analysis of a Lending Club to find out the driving factors behind loan default


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
This is a group case study in which I use EDA (Exploratory Data Analysis) to analyze a finance company. This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.

In this project, we need to analyze the data and find out the driving factors behind loan default (the loans that were charged off), so the company can take those factors into consideration when deciding whether to accept a loan or not.

We use the `loan.csv` (included in this repository) to analyze the data.

***Since this is a group case study, but due to a technical issue in UpGrad, I was not assigned to any groups.***

## Conclusions
Those are the conclusions retrieved from the analysis, further information can be found in the Notebook
- Lending Club should be careful of the loans which term is 60-month, as the Charged Off Rate is much higher than 36-month loans (30% compare to 15%)
- Lending Club should be cautious when the lending purpose is **Small Business**, especially when the applicants had already had a public record bankruptcy
- Leading Club should also take the applicant's LC assigned loan grade and subgrade into consideration. Grade A and B are more likely to repay the loan, while F and G are more likely to charge off. F5 has the highest charged off rate, so Lending Club should be careful of F5 applicants.
- Among all the state, Lending Club should be wary of Nebraska (NE) loans, the charge off rate in this state is very high (over 60%)
- The higher the loan amount, the higher the charged off rate, Lending Club should be careful of the loans that has the amount over 15000
- Annual income below 75000 is very low in Verification Status (Over 40% Unverified), and thus the Charged Off Percentage is high among those applicants whose income is below 75k. Lending Club need to be more careful with those applicants.


## Technologies Used
- python - version 3.9
- pandas - version 1.4.3
- notebook - version 6.4.12
- matplotlib - version 3.5.2
- seaborn - version 0.11.2

## Contact
Created by [@phucanthony] - feel free to contact me!

