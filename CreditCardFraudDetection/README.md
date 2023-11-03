# Credit Card Fraud Detection
Welcome to the Credit Card Fraud Detection project!

## Overview
The dataset provided focuses on credit card transactions in September 2013 by European cardholders. Its primary objective is to aid credit card companies in detecting fraudulent transactions, ensuring customers are not wrongly charged for unauthorized purchases.
The dataset encompasses transactions spanning two days, encompassing a total of 284,807 transactions. Out of these, 492 are identified as fraudulent, constituting only 0.172% of the total.

## Dataset Details
- Features: The dataset exclusively consists of numerical input variables derived from Principal Component Analysis (PCA) transformation. Due to confidentiality constraints, the original features and additional background information cannot be disclosed. The features labeled V1 through V28 represent the confidential features, with 'Time' and 'Amount' being the only unaltered features.
- 'Time': Signifies the seconds elapsed since the first transaction.
- 'Amount': Indicates the transaction amount.
- 'Class': Serves as the response variable, assuming a value of 1 in cases of fraud and 0 otherwise.

## Project Structure
The project is organized into the following directories:<br>
<br>[Dataset](https://github.com/YomnaEisa/Codsoft/tree/main/CreditCardFraudDetection/Dataset): This directory contains the dataset used for training and model evaluation.<br>
<br>[Exploratory Data Analysis](https://github.com/YomnaEisa/Codsoft/tree/main/CreditCardFraudDetection/Exploratory%20Data%20Analysis): This directory contains the Jupyter Notebook used for Exploratory Data Analysis where the data is explored, preprocessed and hypotheses were formed and validated.<br>
<br>[Model](https://github.com/YomnaEisa/Codsoft/tree/main/CreditCardFraudDetection/Model): The trained model is saved in this directory.<br>
<br>[requirements.txt](https://github.com/YomnaEisa/Codsoft/blob/main/CreditCardFraudDetection/requirements.txt): List of Python dependencies required to run the project.<br>

## Getting Started
1. Clone the repository:<br>
   git clone https://github.com/YomnaEisa/CreditCardFraudDetection.git<br>
   cd CreditCardFraudDetection

<br>

2. Install the required packages:<br>
   pip install -r requirements.txt
