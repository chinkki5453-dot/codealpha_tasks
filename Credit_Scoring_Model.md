Credit Scoring Model
File: credit_scoring.ipynb

Objective
To predict whether a loan applicant is likely to default based on various financial and personal attributes.

Dataset Overview
The project uses a synthetic dataset consisting of 1,000 applicants.

	1. Features: Income, Age, Loan Amount, Credit Score, and Years Employed.

	2. Target Variable: Binary classification where 0 represents "No Default" and 1 represents "Default".

Machine Learning Models
Two classification models were implemented and compared:

	1. Logistic Regression.

	2. Random Forest Classifier.

Key Results
	1. The Random Forest model achieved perfect accuracy on this synthetic dataset.

	2. Conclusion: While perfect accuracy was reached here due to clearly defined rules in the synthetic data, real-world data is typically noisier, making such results unlikely in practice.