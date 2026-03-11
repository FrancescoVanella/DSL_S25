# Predicting Real Estate Prices on a U.S. Listings Dataset Using XGBoost and Random Forest

This repository contains the final project of the course *Data Science Lab* of Politecnico di Torino.

## Assignment and Report

Predict the monthly rental price of U.S. apartment listings from structured and unstructured features. See [assignment](Data_Science_Lab__Project_Assignment_Summer_2025.pdf) and [report](Report.pdf) for details of the implementation.

## Repository Structure

```
├── notebooks/
│   ├── EDA.ipynb             # Exploratory data analysis
│   └── main.ipynb            # Preprocessing, model training, evaluation, and testing
├── data/
│   └── raw/                  # CSV files (development.csv, evaluation.csv)
├── Report.pdf        
├── Data_Science_Lab__Project_Assignment_Summer_2025.pdf 
├── submission.csv
├── requirements.txt
└── .gitignore
```

## Set up and Execution

```bash
pip install -r requirements.txt
```

1. `EDA.ipynb` — exploratory data analysis
2. `main.ipynb` — reads from `data/raw/`, trains models, writes `submission.csv`
