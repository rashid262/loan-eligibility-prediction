# Loan Eligibility Prediction Project

## **Overview**
This project aims to predict the eligibility of a loan applicant based on various parameters. In the financial sector, it's crucial to assess the risk associated with lending and determine whether an applicant can repay the loan. Machine learning models like the one developed in this project prove to be effective tools for this purpose.

## **Dataset**
The dataset used for this project was obtained from Kaggle. It includes the following columns:
- Loan_ID
- Gender
- Married
- Dependents
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area
- Loan_Status
- LoanAmount_log (derived from LoanAmount through preprocessing)

## **Preprocessing**
In the preprocessing stage, null values were filled, and normalization was performed using the logarithm function. This step ensures that the data is suitable for training machine learning models.

## **Algorithms Used**
Two machine learning algorithms were implemented for this project:
- Decision Tree
- Naive Bayes

## **Performance**
- Decision Tree: Achieved an accuracy of 70.73%
- Naive Bayes: Achieved an accuracy of 82.93%

## **Testing**
The trained models were tested with an unlabeled dataset obtained from the same source to assess their performance in real-world scenarios.

## **Libraries Used**
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## **Future Improvements**
In the future, this model will be further improved by implementing additional algorithms and exploring more advanced techniques for feature engineering and model optimization.

## **Contributing**
Contributions to this project are welcome. If you have suggestions for improvements or want to contribute code, feel free to submit a pull request.

## **License**
This project is licensed under the [MIT License](LICENSE).
