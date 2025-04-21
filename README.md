# TASK-1-ELEVATELABS
# 🧹 Task 1: Data Cleaning and Preprocessing

This repository contains the solution for **Task 1** of the Data Analyst Internship. The task involves cleaning and preparing a raw Amazon dataset using Python (Pandas). This is a crucial step before performing any analysis or modeling.

## 📁 Files Included

- `amazon.csv` – Original dataset.
- `amazon_cleaned_task1.csv` – Cleaned version of the dataset.
- `task1_cleaning_amazon.ipynb` – Jupyter notebook containing all preprocessing steps.
- `README.md` – Overview of the task and solution.

## 📌 Objectives

- Identify and handle missing values
- Remove duplicate rows
- Standardize and clean text and numeric data
- Convert price and percentage formats to numerical
- Rename columns for clarity and consistency
- Prepare dataset for further analysis

## 🛠 Tools Used

- Python
- Pandas
- NumPy
- Seaborn & Matplotlib (for visualization)

## 🧾 Summary of Changes

| Step                  | Description |
|-----------------------|-------------|
| Missing values        | Detected and marked (e.g., in `rating_count`, `rating`) |
| Duplicate rows        | Checked – none found |
| Price & discount data | Cleaned and converted to float values |
| Column names          | Renamed to lowercase, snake_case |
| Data types            | Corrected for analysis (e.g., rating as float) |

## 📊 Next Steps

This cleaned dataset is now ready for:
- Exploratory Data Analysis (EDA)
- Visualizations
- Modeling or segmentation
- Sentiment analysis on review content

## ✅ Submission Guidelines Followed

- Cleaned using Python
- Includes notebook, dataset, and this README
- Ready for GitHub upload

