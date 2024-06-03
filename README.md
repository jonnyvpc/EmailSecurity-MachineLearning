# Email Security Machine Learning
Use machine learning to classify email as spam or ham. 

# Email Classification for Bank Security

## Overview
This project aims to develop a machine learning model for email classification to enhance security for JPMorgan's banking operations. The model distinguishes between spam and ham (non-spam) emails, aiding in safeguarding against potential threats.

## Dataset
The dataset used for training and testing the model consists of emails from the Enron email corpus. It includes both spam and ham emails, providing a diverse set of examples for training the classifier.

## Steps

### Step 1: Data Collection and Preprocessing
The Enron email dataset is collected and preprocessed to prepare it for training the machine learning model. This involves reading the emails, cleaning the text data, and structuring it into a format suitable for training the classifier.

### Step 2: Model Training
A machine learning model is trained using the preprocessed email data. The model utilizes the scikit-learn library and logistic regression for classification. The dataset is split into training and test sets, and the model is trained on the training set.

### Step 3: Model Evaluation
The performance of the trained model is evaluated using various metrics such as accuracy, confusion matrix, and classification report. This step provides insights into how well the model distinguishes between spam and ham emails.

### Step 4: Feature Analysis
The top features created by the vectorizer and coefficients from the model are analyzed to understand the most indicative factors for spam or ham emails. This aids in interpreting the model's decision-making process.

## Usage
To use this project, follow these steps:
1. Clone the repository to your local machine.
2. Install the required dependencies listed in the `requirements.txt` file.
3. Run the Jupyter Notebook `email_classification.ipynb` to train and evaluate the model.

## Conclusion
This project demonstrates the development of a machine learning model for email classification, specifically tailored to enhance security for JPMorgan's banking operations. By accurately distinguishing between spam and ham emails, the model contributes to mitigating potential security threats.

## Contributors
- [Jonny Jackson](https://github.com/jonnyvpc)

Feel free to contribute to this project by submitting pull requests or opening issues for any improvements or suggestions!

