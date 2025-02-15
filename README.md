# Transaction Monitoring - Money Laundering Detection

This project aims to build a machine learning model for transaction monitoring, specifically to identify potential cases of money laundering. Using a dataset of transactions, the model is trained to classify each transaction as either a case of fraud (money laundering) or a normal transaction.

## Objective

The goal of this project is to create an automated system that can classify transactions based on their likelihood of being involved in fraudulent activities such as money laundering. By training a model on historical transaction data, the system can make predictions on new transactions to help detect suspicious behavior.

## Dataset

The dataset used in this project contains a variety of transaction details, including transaction amount, time, sender, receiver, and other relevant features. Each transaction is labeled as either fraudulent or normal.

## Outputs

After training the model and making predictions, the following output was obtained:

- **Fraud labelled transactions**: 41,250
- **Normal transactions**: 9,169

These outputs show how many transactions were predicted to be fraudulent versus normal, helping to identify potential risks in financial systems.

## How to Run the Project

### Requirements

Before running the project, make sure to install the necessary dependencies:

```bash
pip install -r requirements.txt
```

### Steps

1. **Data Cleaning**: The dataset is cleaned by handling missing values, removing duplicates, and converting data into the appropriate format.
2. **Data Splitting**: The dataset is split into training and test sets for model evaluation.
3. **Model Training**: A machine learning model is trained on the dataset to predict whether a transaction is fraudulent.
4. **Prediction**: The trained model is used to predict transaction labels on unseen data.

## Key Components

- **Data Preprocessing**: Code for cleaning and preparing the data before feeding it into the model.
- **Model**: Machine learning model built to classify transactions into fraud or normal categories.
- **Evaluation**: Evaluation metrics like accuracy, precision, recall, and F1 score to assess the model's performance.

## Future Improvements

- Incorporating additional features for more accurate predictions.
- Experimenting with different machine learning algorithms to improve model performance.
- Developing a real-time system for continuous monitoring of transactions.

## License

This project is open-source and available under the MIT License.
