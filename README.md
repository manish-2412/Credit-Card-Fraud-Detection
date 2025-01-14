# Credit-Card-Fraud-Detection

This project is about detecting fraudulent transactions in a credit card dataset using a Logistic Regression model.

Dataset Information

The dataset contains two types of transactions:

	•	0 → Legitimate (normal) transactions
	•	1 → Fraudulent transactions

The dataset is imbalanced, meaning there are far more legitimate transactions than fraudulent ones.

Steps

	1.	Load the Dataset
The dataset is loaded and basic checks like missing values and data statistics are performed.
	2.	Balance the Dataset
	•	Legitimate transactions are sampled to match the number of fraudulent transactions.
	•	Both are combined into a new balanced dataset.
	3.	Split the Data
The dataset is split into training and testing sets (80% training, 20% testing).
	4.	Train the Model
A Logistic Regression model is trained using the training data.
	5.	Evaluate the Model
Accuracy is calculated for both the training and testing data.

Results

	•	The model achieves good accuracy on both training and testing data, showing its ability to detect fraudulent transactions effectively.

How to Run

	1.	Clone or download the project.
	2.	Ensure the required Python libraries are installed (numpy, pandas, sklearn).
	3.	Place the dataset file (creditcard.csv) in the same directory as the code.
	4.	Run the Python script to see the results.

Acknowledgment

Dataset Source: Kaggle Credit Card Fraud Dataset

This project provides a simple and effective way to detect credit card fraud.
