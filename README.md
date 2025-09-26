# Synthetic Financial Transaction Data Generator

A comprehensive Jupyter Notebook for generating realistic synthetic financial transaction data for behavioral analysis and testing purposes.

## 📋 Overview

This project creates synthetic financial transaction data that mimics real banking patterns while maintaining complete data privacy. The generated data includes realistic transaction amounts, types, and temporal patterns suitable for modeling, testing, and analysis.

## 🚀 Features

- **Realistic Data Patterns**: Time-based weighting for business hours and weekdays
- **Multiple Transaction Types**: Deposit, Withdrawal, Payment, Transfer, Refund
- **Smart Amount Distributions**: Different statistical distributions per transaction type
- **Comprehensive Validation**: Statistical analysis and data quality checks
- **Visual Analytics**: Built-in charts and graphs for pattern analysis
- **Privacy Compliant**: No real customer information used

## 📊 Generated Data Fields

| Field | Description | Example |
|-------|-------------|---------|
| `transaction_id` | Unique transaction identifier | TXN000001 |
| `transaction_amount` | Transaction amount in USD | 150.75 |
| `transaction_type` | Type of transaction | PAYMENT, DEPOSIT, etc. |
| `timestamp` | Date and time of transaction | 2023-06-15 14:30:25 |
| `year`, `month`, `day` | Temporal breakdown components | 2023, 6, 15 |
| `hour` | Hour of day | 14 |
| `day_of_week` | Day of week (0=Monday) | 2 |
| `is_weekend` | Weekend indicator | 0 or 1 |

## 🛠️ Installation & Setup

### Prerequisites
- Python 3.7+
- Jupyter Notebook/JupyterLab

### Required Packages
```bash
pip install pandas numpy faker matplotlib seaborn
