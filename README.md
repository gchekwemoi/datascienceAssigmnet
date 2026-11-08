# Data Science Lifecycle: Assignment 1


**Name:** Chekwemoi Gloria
**Course:** MSDS

## Objective
Use exploratory data analysis (EDA) and statistical techniques on the automobile dataset to find the variables that have the most impact on car price, and give a pricing recommendation for a car dealer.

## Files in this repository

| File | Description |
|---|---|
| `Assignment1_Chekwemoi.ipynb` | Executed Jupyter notebook (Python code, outputs and an explanation of every output) |
| `automobileEDA.csv` | Original dataset provided for the assignment |
| `Chekwemoi_Data.csv` | Cleaned dataset produced in Question 1 |

## What the notebook covers

1. **Data exploration and cleaning:** structure of the data, missing values, duplicates and outliers, and saving the cleaned dataset.
2. **Descriptive statistics and patterns:** summary statistics, frequency counts and distribution plots.
3. **Group averages:** average price by drive-wheels, body-style and make, with charts and a heatmap.
4. **Effect of variables on price:** continuous variables (scatter plots and correlation), categorical variables (boxplots and ANOVA) and two categorical variables (cross-table and chi-square test).
5. **Feature selection and recommendation:** `SelectKBest` (F-test) to find the most important variables, and a short recommendation for a car dealer.

## Key findings

- **Cleaning:** 4 missing `stroke` values and 1 missing `horsepower-binned` value were filled; there were no duplicate rows; high-priced luxury cars (BMW, Mercedes-Benz, Jaguar, Porsche) were kept as genuine outliers.
- **Most expensive groups:** rear-wheel drive cars, hardtops and convertibles, and the Jaguar and Mercedes-Benz brands.
- **Cheapest groups:** front-wheel drive cars, hatchbacks and the Chevrolet brand.
- **Main drivers of price:** engine size, curb weight and horsepower (the size and power of the car), followed by make, drive-wheels and number of cylinders.
- **Little or no effect:** height, peak RPM, compression ratio, stroke and number of doors.

## How to run

1. Open `Assignment1_Chekwemoi.ipynb` in [Google Colab](https://colab.research.google.com) (File > Upload notebook, or File > Open notebook > GitHub).
2. Click **Runtime > Run all**. The notebook reads `automobileEDA.csv` from this repository.

## Tools used
Python, pandas, NumPy, Matplotlib, Seaborn, SciPy, scikit-learn, Google Colab, GitHub.
