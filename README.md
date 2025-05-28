# Introduction-of-Data-Mining

### 📦 GitHub Repository Overview

This project implements and evaluates an enhanced anomaly detection algorithm based on Local Outlier Factor (LOF), referred to as LOF+, using the IEEE-CIS Fraud Detection Dataset. The source code, selected datasets, and experimental results are available in the following GitHub repository:

###  🔗 GitHub Repository:
https://github.com/hjshin21/Introduction-of-Data-Mining

## 📁 Repository Structure

| File / Folder         | Description                                                              |
|-----------------------|--------------------------------------------------------------------------|
| `train_transaction.csv` | Subset (N=1500) of transaction records from the IEEE-CIS Fraud Detection Dataset |
| `train_identity.csv`    | Matching identity information for the selected transactions             |
| `only_LOF.ipynb`        | Baseline LOF implementation and evaluation                             |
| `updated_LOF.ipynb`     | Enhanced LOF+ algorithm implementation and performance comparison       |
| `README.md`             | Project overview, usage instructions, and dataset description           |


### 📊 Performance Summary (N = 1500)

| Model  | Precision (Fraud) | Recall (Fraud) | ROC AUC |
|--------|-------------------|----------------|---------|
| LOF    | 0.05              | 0.13           | 0.6512  |
| LOF+   | 0.05              | 0.19           | 0.7361  |

Please refer to the full report for detailed plots and evaluation metrics.
