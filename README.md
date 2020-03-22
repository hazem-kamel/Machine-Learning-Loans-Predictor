# Machine-Learning-Loans-Predictor
Machine Learning Loans Predictor ,Cleaning Data and Classifying using KNN , Decision Tree, Support Vector Machine and Logistic Regression , F1 and Jaccard accuracy for evaulating results 

#### Introduction
The two most critical questions in the lending industry are: 1) How risky is the borrower? 2) Given the borrower’s risk,
should we lend him/her? The answer to the first question determines the interest rate the borrower would have.
Interest rate measures among other things (such as time value of money) the riskness of the borrower, i.e.
the riskier the borrower, the higher the interest rate. With interest rate in mind, 
we can then determine if the borrower is eligible for the loan.

#### Data Section
This dataset is about past loans. The Loan_train.csv data set includes details of 346 customers whose loan are
already paid off or defaulted. It includes following fields:

|  Field  | Description |
| :---: | :---: |
| Loan_status | Whether a loan is paid off on in collection |
|  Principal | Basic principal loan amount |
| Terms | Origination terms which can be weekly (7 days), biweekly, and monthly payoff schedule |
| Effective_date | When the loan got originated and took effects | 
| Due_date | Since it’s one-time payoff schedule, each loan has one single due date |
| Age | Age of applicant
| Education | Education of applicant | 
| Gender | The gender of applicant | 

Data is then transformed into a dataframe using pandas , visualized and pre-processed using matplotlib , seaborn and one hot encoding technique to convert categorical varables to binary variables and append them to the feature Data Frame¶. 

#### Methodology Section
The Dataframe were splited to generate a training set and a test set to increase the accuracy , Scikitlearn library were used to classify the data using this techniques :

 * K Nearest Neighbor(KNN)
 * Decision Tree
 * Support Vector Machine
 * Logistic Regression
 
 The accuracy were then tested using the test set with accuracy_score, f1_score ,jaccard_similarity_score.
 
 
