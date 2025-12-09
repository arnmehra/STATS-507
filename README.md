#STATS 507 Final Project: Credit Card Fraud/Anomaly Detection

**Author:** Arnav Mehra
**Email:** arnmehra@umich.edu

## Project Overview

Machine learning pipeline for credit card fraud detection using 1.85M+ transactions.

**Key Results:**
- Logistic Regression: 75.70% fraud detection rate
- Random Forest: 98% precision, 71.71% recall
- Isolation Forest: 1.19% recall (shows unsupervised limitations)

## Files

- `STATS 507_Final Project_Credit Card Anomaly Detection.ipynb` - Complete project code
- `STATS 507_Final Project_Credit Card Anomaly Detection.pdf` - 2-page project report
- `requirements.txt` - Python dependencies

## Data Setup

**Dataset:** [Credit Card Transactions](https://huggingface.co/datasets/pointe77/credit-card-transaction)

### Download Data:
1. Go to: https://huggingface.co/datasets/pointe77/credit-card-transaction
2. Download both CSV files:
   - `credit_card_transaction_train.csv` as 'credit_card_transaction_data.csv'
   - `credit_card_transaction_test.csv` as 'credit_card_transaction_data_new.csv'
3. Place them in a `data/` folder

**Note:** CSV files not included in GitHub due to size (~500MB total)

## Running the Project
```bash
# Install dependencies
pip install -r requirements.txt

# Run Jupyter notebook
jupyter notebook STATS 507_Final Project_Credit Card Anomaly Detection.ipynb
```

## Results Summary

See `STATS 507_Final Project_Credit Card Anomaly Detection.pdf` for detailed analysis.

| Model | Recall | Precision |
|-------|--------|-----------|
| Logistic Regression | 75.70% | 2% |
| Random Forest | 71.71% | 98% |
| Isolation Forest | 1.19% | 1% |