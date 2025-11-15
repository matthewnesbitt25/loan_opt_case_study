# Loan Approval Optimization (Case Study Analysis)

This project analyzes borrower characteristics to identify key drivers of loan approval and optimize lender assignment strategy to maximize expected revenue per application.  
The project was completed as part of a technical assessment for a loan analytics case study.  
**The dataset is not included due to confidentiality.**

## Overview

The goal of this analysis was to:
- Understand which borrower features most strongly impact loan approval rates  
- Compare lender performance across borrower segments  
- Build an approval–revenue model using approval rates × bounty structure  
- Recommend an optimized lender assignment strategy  
- Quantify the expected revenue lift from the optimized approach

## Methods & Techniques

**Data Cleaning & Preparation**
- Normalized column names  
- Handled missing values  
- Converted ordinal categories (e.g., FICO score groups)  
- Engineered metrics such as housing-to-income ratio

**Analytics & Modeling**
- Exploratory data analysis (EDA)  
- Approval rate modeling  
- Segmentation by FICO tier  
- Revenue matrix generation  
- Optimal lender selection per segment  

**Visualization**
- Approval rate charts  
- FICO score group comparisons  
- Revenue-per-application comparisons

Results

- Identified strong predictors of approval, especially **FICO score** and **loan amount**  
- Built lender approval & revenue matrices across borrower segments  
- Recommended an optimized lender assignment strategy  
- Achieved an estimated **22% increase in expected revenue per application**  
- Delivered insights via a business-focused presentation supported by technical analysis

## Repository Structure

loan-approval-optimization/
│
├── notebook/
│ └── complete_exploration.ipynb
│ └── apprvrate_by_loanamt_lender.png
│ └── apprvrate_by_loanamt.png
│ └── rev_per_app_difference.png
│
├── visualizations/
│ └── apprvrate_by_FICO_group.png
│
├── data/
│ └── README.md
│
├── scripts/
│ └── analysis.py
│
└── README.md

 ## Tools Used

- **Python**  
- **Pandas**  
- **NumPy**  
- **Matplotlib**  
- **Seaborn**  
- **Jupyter Notebook**  
- **VS Code**

## Data Omission Notice

The dataset used in the original case study is **confidential** and cannot be shared.  
This repository includes only my **analysis code** and **visualizations**, not the original data.
