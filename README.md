# FraudDetection-using-LogisticRegression

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter%20Notebook-6.2.0-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## Overview

This project implements a Fraud Detection model using Logistic Regression. The objective is to predict fraudulent transactions for a financial company and develop actionable insights from the model's results. The dataset used for training and testing is available on Kaggle. You can find the dataset [here](https://www.kaggle.com/datasets/chitwanmanchanda/fraudulent-transactions-data?resource=download).

## Project Structure

```
FraudDetection.ipynb
LICENSE
README.md
```

## Dependencies

- Python 3.7+
- Jupyter Notebook 6.2.0
- Pandas
- Numpy
- Scikit-learn
- Matplotlib
- Seaborn

## Features

- Logistic Regression Model
- Exploratory Data Analysis (EDA)
- Data Preprocessing and Visualization

## Instructions

1. Clone the repository:

```bash
git clone https://github.com/your_username/FraudDetection.git
cd FraudDetection
```

2. Install the required dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

3. Download the dataset from the provided Kaggle link and place it in the project directory.

4. Open the Jupyter Notebook "FraudDetection.ipynb" using Jupyter Notebook.

5. Follow the step-by-step instructions in the notebook to run the code cells and execute the Fraud Detection model.

## Project Description

In this project, I have developed a Fraud Detection model using Logistic Regression. The goal is to predict fraudulent transactions for a financial company based on historical transaction data. The dataset contains information about transaction types, amounts, customer balances, and other relevant features. The Logistic Regression model is trained on this data to identify patterns and predict fraudulent behavior.

## Data Description

The dataset includes the following columns:

- `step`: Maps a unit of time in the real world (1 step = 1 hour).
- `type`: Transaction types (CASH-IN, CASH-OUT, DEBIT, PAYMENT, TRANSFER).
- `amount`: Amount of the transaction in local currency.
- `nameOrig`: Customer who initiated the transaction.
- `oldbalanceOrg`: Initial balance before the transaction.
- `newbalanceOrig`: New balance after the transaction.
- `nameDest`: Customer who is the recipient of the transaction.
- `oldbalanceDest`: Initial balance of the recipient before the transaction.
- `newbalanceDest`: New balance of the recipient after the transaction.
- `isFraud`: Binary label indicating whether the transaction is fraudulent (1) or not (0).

## Model Evaluation

The model is evaluated on various performance metrics, including accuracy, precision, recall, and F1-score. The confusion matrix is used to assess the model's ability to correctly classify fraudulent and non-fraudulent transactions.

## Results and Conclusion

The results of the Fraud Detection model are analyzed, and actionable insights are derived from the model's predictions. The project's findings and recommendations are discussed in the Jupyter Notebook.

## Steps to Run the Notebook

1. Install Python and Jupyter Notebook on your system.
2. Clone the repository and navigate to the project directory.
3. Install the required dependencies.
4. Download the dataset from the provided Kaggle link and place it in the project directory.
5. Open the Jupyter Notebook "FraudDetection.ipynb."
6. Follow the step-by-step instructions in the notebook to execute the code cells and run the Fraud Detection model.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
