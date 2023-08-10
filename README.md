# Project Name
> Lending Club EDA Case Study


## Table of Contents
* [General Info](#general-information)
* [Hypothesis](#Hypothesis)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss).borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
- Consumer finance company  wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.The company can utilise this knowledge for its portfolio and risk assessment.
- Dataset contains the complete loan data for all loans issued through the time period 2007 t0 2011. Also,Data dictionary has business gloassary details

## Hypothesis
- Longer terms might have higher default rates.
- Higher interest rates might lead to a higher likelihood of default.
- Shorter employment lengths might be associated with higher default rates.
- Borrower's annual income could influence their ability to repay the loan.
- Higher DTI ratios could be associated with higher default rates.



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- loan_amnt: Higher loan amounts might slightly increase the chance of default, but the effect is minimal.
- funded_amnt: Like with loan_amnt, higher funded amounts might have a slight impact on default rates.
- funded_amnt_inv: The impact of funded_amnt_inv on default rates appears to be minimal.
- term:Longer loan terms might be associated with a higher likelihood of default.
- int_rate: Higher interest rates might be associated with a higher chance of default.
- installment: The impact of installment on default rates seems to be minimal.
- emp_length: There seems to be a minimal impact of employment length on default rates.
- annual_inc: Higher annual income might slightly reduce the likelihood of default.
- dti: Higher DTI ratios might have a small impact on default rates.
- home_ownership: Different categories of home ownership (rent, own, mortgage) might impact loan default rates.
- purpose: The purpose of the loan (e.g., debt consolidation, medical expenses) might indicate the borrower's financial situation and impact their ability to repay.
- grade : Grades are assigned to loans based on credit risk. These could be significant indicators of default.
- Segmentation: In general, debt consolidation loans have the highest default rates. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python
- GitHub
- Jupyter Notebook
- Python Libraries: Pandas,Seaborn,Matplotlib,Numpy

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements


## Contact
Created by [@Trezajacob & Yukti] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->