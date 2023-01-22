# Lending-Club-Case-Study

## Business Objective
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 

## Business Understanding

You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

 The data given below contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
 
 ![Loan_image](https://user-images.githubusercontent.com/39112641/213905708-6b24cbc3-6e5a-4b6d-9a57-7c0bb0d948c9.png)

When a person applies for a loan, there are two types of decisions that could be taken by the company:

<ul>
<li> <b>Loan accepted:</b> If the company approves the loan, there are 3 possible scenarios described below:</li>
  <ol>
  <li> <b>Fully paid:</b> Applicant has fully paid the loan (the principal and the interest rate)

  <li> <b>Current:</b> Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

  <li> <b>Charged-off:</b> Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 
  </ol>
<li> <b>Loan rejected:</b> The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)</li>
</ul>

## Solution Demonstrated in Jupyter Notebook File:
https://github.com/mrm1404/Lending-Club-Case-Study/blob/main/Madhav%20Mehta.ipynb

## Recommendation Given:
https://github.com/mrm1404/Lending-Club-Case-Study/blob/main/LendingClub.pdf
