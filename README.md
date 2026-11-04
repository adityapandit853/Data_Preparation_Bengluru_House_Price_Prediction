# Bengaluru House Price Prediction – Data Preparation

## Project Overview
This project focuses on preparing the Bengaluru House Price Dataset for a Simple Linear Regression model. Data preparation is performed using Python libraries to clean and transform the dataset.

## Dataset
**Dataset Name:** Bengaluru House Price Data

**Source:** [Kaggle – Bengaluru House Price Dataset](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data)

The project uses two columns:
- `total_sqft`: Total area of the house in square feet.
- `price`: House price in Indian lakhs.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Data Preparation Steps
1. Load the Bengaluru House Price Dataset.
2. Select the required columns (`total_sqft` and `price`).
3. Check dataset information and data types.
4. Identify missing values.
5. Remove missing values.
6. Convert square-foot ranges into numerical values.
7. Remove invalid and zero values.
8. Identify duplicate records.
9. Remove duplicate records.
10. Generate statistical summaries.
11. Visualize the relationship between house area and price.
12. Save the cleaned dataset as `Cleaned_House_Data.csv`.

## Installation

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

## How to Run

1. Place `Bengaluru_House_Data.csv` in the project folder.
2. Run the Python script:

```bash
python data_preparation.py
```

3. The cleaned dataset will be generated as:

`Cleaned_House_Data.csv`

## Output
A cleaned CSV file containing numerical house area and price values, ready for Simple Linear Regression.

## Objective
To clean and prepare real-world housing data for machine learning and improve its suitability for regression analysis.
