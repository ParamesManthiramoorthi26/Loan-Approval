# Predicting Loan Approvals: Machine Learning Insights
## Project Overview
Home loan approval is crucial for both financial institutions and applicants. Accurate decision-making relies on various applicant details such as income, credit history, property area, and employment status. This project leverages machine learning to predict loan approval outcomes, ensuring efficiency, reliability, and fairness in decision-making.
## Dataset Description
### Dataset Overview:
* Shape: 953 rows and 13 columns.
* Purpose: The dataset contains information about loan applications and their approval statuses. It is useful for exploring factors influencing loan approval decisions.
* Columns and Descriptions:
1. Loan_ID: Unique identifier for each loan.
2. Gender: Gender of the applicant (e.g., Male, Female).
3. Married: Marital status of the applicant (e.g., Yes, No).
4. Dependents: Number of dependents supported by the applicant.
5. Education: Education level of the applicant (e.g., Graduate, Not Graduate).
6. Self_Employed: Whether the applicant is self-employed (e.g., Yes, No).
7. ApplicantIncome: Income of the loan applicant.
8. CoapplicantIncome: Income of the co-applicant, if any.
9. LoanAmount: Loan amount requested (in thousands).
11. Loan_Amount_Term: Duration of the loan (in months).
12. Credit_History: Whether the applicant has a good credit history (1 = Yes, 0 = No).
13. Property_Area: Area where the property is located (e.g., Urban, Rural, Semiurban).
14. Loan_Status: Loan approval status (Y = Approved, N = Not Approved).

## Objective
Evaluate and compare the accuracy of different machine learning models in predicting home loan approval.
The models analyzed include Logistic Regression, Random Forest, Decision Tree, Gradient Boosting Machines (GBM), Naive Bayes (NB), and Support Vector Machines (SVM).
Identify the best-performing model based on accuracy, precision, recall, and F1-score.
## Technologies & Tools Used
*Programming Language:* Python
*Libraries:* Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
*Techniques:* Data Preprocessing, Feature Engineering, Model Evaluation
## Model Performance Comparison
![image](https://github.com/user-attachments/assets/7249cb8a-8892-4b72-b59e-e236711f0de5)

## My Observations
*Best Accuracy:* Naive Bayes (0.80), followed closely by Logistic Regression (0.792).
*Best Precision for Class 1:* Logistic Regression (0.80), followed by Naive Bayes (0.79).
*Best Recall for Class 1:* Naive Bayes (0.96), followed by Logistic Regression (0.92).
*Best F1-Score for Class 1:* Naive Bayes (0.87), followed by Logistic Regression (0.86).
## Conclusion
* Naive Bayes and Logistic Regression performed the best overall, with high accuracy, recall, and F1-score.
* SVM also performed well, balancing precision and recall.
* Decision Tree and Random Forest had the lowest accuracy (0.65) and performed worse than other models.
* Gradient Boosting showed moderate performance but was not as strong as Naive Bayes or Logistic Regression.
