## FinGuard AI: Behavioral Fraud Detection Dataset

This dataset is a synthetic yet behaviorally realistic financial dataset designed for fraud detection and risk modeling.

### 🔹 Dataset Structure

* users.csv → User demographics, income, credit score, risk profile
* accounts.csv → Account details, balances, KYC status
* transactions.csv → Transaction-level data with timestamps and fraud labels

### 🔹 Key Features

* Temporal transaction patterns (60-day simulation)
* Income-based spending behavior
* Multi-account relationships
* Fraud injection based on real-world scenarios:

  * High-value anomalies
  * Transaction bursts
  * International fraud patterns

### 🔹 Target Variable

* is_fraud → 0 (legit), 1 (fraud)

### 🔹 Use Cases

* Fraud detection models
* Anomaly detection
* Risk scoring systems
* Financial behavior analysis

### 🔹 Note

This dataset is synthetically generated with controlled logic to simulate realistic financial behavior.
