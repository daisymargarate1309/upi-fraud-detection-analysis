# UPI Fraud Detection Analysis

Exploratory analysis of 250,000 UPI transactions to understand when, where and how fraud occurs.

## Dataset
[UPI Transactions 2024 (Kaggle)](https://www.kaggle.com/datasets/skullagos5246/upi-transactions-2024-dataset
)

Download the CSV from the link above and keep it in the same folder as the notebook.

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn

## Key Findings
- Only 0.19% of transactions are fraud (480 out of 250,000), so the data is heavily imbalanced.
- No single feature (transaction type, category, device, network, bank, state) strongly predicts fraud.
- Fraud and genuine transaction amounts look similar (median Rs. 618.5 vs Rs. 629).
- Only mild variation in fraud rate by hour of day and day of week.

## How to Run
1. Download the dataset from the Kaggle link above.
2. Open the notebook in Jupyter or Google Colab.
3. In Colab, upload the CSV to the session, or skip the Drive cell (cell 2) if you upload directly.
4. Run all cells.
