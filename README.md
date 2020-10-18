# Lending_Club

LendingClub is a US peer-to-peer lending company and the world's largest peer-to-peer lending platform.

Lending Club enables borrowers to create unsecured personal loans between 1.000 and 40.000 USD. The standard loan period is three years. Investors can search and browse the loan listings on Lending Club website and select loans that they want to invest in based on the information supplied about the borrower, amount of loan, loan grade, and loan purpose. Investors make money from interest. Lending Club makes money by charging borrowers an origination fee and investors a service fee.

For the purposes of this project, data on loans granted through the Lending Club in the years 2007-2011 were used. Each loan has an indication of whether it has finally been repaid (Fully Paid or Charged off in the loan_status column). Your task is to build a classification model that, based on this data, will predict with a certain accuracy whether the potential borrower will repay his debt on the loan taken. The data set is accompanied by a file with a description of all the variables and the "FICO Score ranged.pdf" file, in which the meaning of one of the columns is described in detail. Below are presented the individual stages of the analysis, the execution of which is necessary to complete the project, and their scoring:

1. Data Processing
2. EDA. Describe the conclusions of each plot, and support your hypotheses with statistical tests such as t-test or Chi-square.
Additionally, answer the following questions: 
a. How does the FICO score relate to the borrower's probability of repaying the loan? 
b. How is the credit age related to the probability of default and is this risk independent or related to the FICO score? 
c. How is the home mortgage status related to the likelihood of default? 
d. How is your annual income related to the probability of default? 
e. How is your employment history related to the probability of default?
f. How is the size of the requested loan related to the probability of default?

3. Feature Engineering - create 20 new variables
4. Modeling
  a. Perform data clustering (try several methods for this purpose, at least 3) and check if there are any borrower segments, use appropriate methods to determine the optimal number of clusters.
  b. Train 5 different models, using a different algorithm for each one, and then compare their performance, take AUROC score as the model quality assessment metric.
  c. Check the operation of previously used methods on compressed data with PCA, compare the results (AUROC score) with the models trained in the previous point. 
  d. Build the final model, the AUROC score of which will be> = 80%, remember to select important variables, cross-validation and fine-tune the model parameters, also think about class balancing.
