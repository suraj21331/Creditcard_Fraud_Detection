# FindDefault-Prediction-of-credit-card-fraud-

# Credit Card Fraud Detection

This project aims to build a machine learning model to detect fraudulent credit card transactions. Using techniques like SMOTE to handle imbalanced data and models such as Logistic Regression, Random Forest, SVM, and KNN, the pipeline predicts whether a transaction is fraudulent based on a dataset of past transactions.


## Project Structure
- `creditcard.csv/`: Contains the dataset used for training and testing the model.
- `Final_Pro/`: Contains Jupyter notebooks used for data exploration, model training, and evaluation.
- `scripts/`: Contains Python scripts for preprocessing, model training, and evaluation.
- `requirements.txt`: Lists all Python dependencies.
- `README.md`: Project documentation and instructions.
- `model/`: Directory where trained models are saved.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/suraj21331/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
   ```

2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Install Jupyter Notebook (optional, for exploring notebooks):
   ```bash
   pip install notebook
   ```


## Dataset
The dataset used for this project is available in the `creditcard.csv/` directory. It contains anonymized credit card transactions with fraud labels.


## Execution

1. Run the preprocessing script to clean and prepare the data:
   ```bash
   python scripts/preprocess.py
   ```

2. Run the model training script:
   ```bash
   python scripts/train_model.py
   ```

3. Evaluate the model performance:
   ```bash
   python scripts/evaluate_model.py
   ```


## Business Impact

Detecting fraudulent transactions is critical for minimizing financial losses and maintaining customer trust. This machine learning solution offers the following benefits to the company:

- **Proactive Fraud Detection**: By identifying fraudulent transactions in real-time, the model helps the company prevent fraudulent activities before they lead to losses.
- **Cost Efficiency**: Automating fraud detection reduces the reliance on manual reviews, saving operational costs.
- **Scalability**: The pipeline is built with scalability in mind, allowing it to handle large volumes of transaction data as the company grows.
- **Improved Customer Experience**: Reducing the number of false positives ensures legitimate transactions are processed smoothly, enhancing customer satisfaction.




