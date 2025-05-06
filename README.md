# Association Rule Mining on Retail Data 🛒

This project implements and compares two association rule mining algorithms—Brute Force (custom-built) and Apriori (via mlxtend)—to uncover purchasing patterns from five major retailers.

## 🧠 Key Features
- Custom brute force algorithm to generate frequent itemsets and rules
- Apriori implementation using `mlxtend` for optimized pattern mining
- Performance benchmarking with execution time comparison
- Interactive CLI for store selection and support/confidence tuning
- Real retail datasets from Amazon, Best Buy, Nike, K-Mart, and Target

## 🛠️ Technologies Used
- Python
- Pandas
- itertools
- mlxtend
- TransactionEncoder
- CSV File Handling

## 📂 Files Included
- `kollikonda_dathwik_midproject.py` – main script
- 5 CSVs – transaction data from each store

## ▶️ How to Run
1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Run the script: `python kollikonda_dathwik_midproject.py`
4. Follow the prompts to select a store and enter support/confidence thresholds

## 📈 Sample Output
- Rule: {Socks} → {Running Shoe} (Confidence: 0.85, Support: 0.55)
- Comparison of brute force vs. apriori execution time

## Author
Dathwik Kollikonda
