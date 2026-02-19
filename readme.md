# Cafe Sales Data Cleaning

This project focuses on cleaning and analyzing the "Dirty Cafe Sales" dataset from Kaggle, which contains 10,000 synthetic transaction records. The goal is to demonstrate data restoration techniques such as imputation and logical reconstruction.

## Repository Structure
```text
├── dataset/                # Data storage
│   ├── raw_data.csv        # Original, raw dataset
│   └── cleaned_data.csv    # Dataset after preprocessing and cleaning
├── process/                # Modular code segments
│   ├── preprocessing.py    # Code for data cleaning and feature engineering
│   └── eda.py              # Code for Exploratory Data Analysis
├── figures/                # Visualizations
│   └── [image_files]       # All plots and charts used in the final report
├── report/                 # Final Deliverables
│   ├── report.ipynb        # Interactive notebook with code and analysis
│   └── report.pdf          # Formatted PDF version of the final report
└── full_code.py            # Complete end-to-end pipeline (All-in-one script)
```


## Getting Started

### 1. Execution

To replicate the entire process from data cleaning to final analysis, run the main script from the **repository root directory** (the folder containing `full_code.py`):

```bash
python full_code.py
```

---

### 2. Logic & Steps

Detailed step-by-step logic and modular scripts are located within the `process/` folder:

- **Data Cleaning**: `process/preprocessing.py`
- **EDA**: `process/eda.py`

---

### 3. Final Results

For the comprehensive summary of findings, methodology, and conclusions, please refer to:

- **Final Report**: `report/report.pdf`
- **Interactive Notebook**: `report/report.ipynb`

---

## How to Run

* **Python Version**: Developed and tested on **Python 3.13.5**.

* **Prerequisites**：
Ensure you have Python installed along with the following libraries:
```bash
pip install pandas numpy matplotlib seaborn xgboost scikit-learn
```

## Team Members(Team 7)
Justine Dugger-Ades (gad2154),
Freya Chen (yc4684),
Xiaohui Ma (xm2352),
Shuxuan Xu (sx2412)
