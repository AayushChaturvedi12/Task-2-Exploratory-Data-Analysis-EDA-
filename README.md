Data Cleaning & Preprocessing

Objective:
Learn how to clean and prepare raw datasets so they are ready for use in Machine Learning models. Proper preprocessing improves model accuracy, efficiency, and reliability.

Tools:
Python – for coding and scripting
Pandas – for handling datasets (loading, cleaning, manipulation)
NumPy – for numerical operations
Matplotlib / Seaborn – for visualization and identifying patterns/issues

Mini Guide / Steps:
Import & Explore the Dataset
Load the dataset using Pandas (pd.read_csv() or similar).
Check data structure with .info(), .describe(), .head().
Identify null values and data types.
Handle Missing Values

Options:
Replace with mean/median (for numerical data).
Use mode/frequent category (for categorical data).
Apply imputation techniques (e.g., forward/backward fill).
Drop rows/columns (if too many missing values).

Encode Categorical Features

Convert categorical variables into numerical formats:

Label Encoding (for ordinal categories).

One-Hot Encoding (for nominal categories).

Normalize / Standardize Features

Normalization (Min-Max Scaling): Scales values between 0 and 1.

Standardization (Z-score): Transforms data to mean = 0 and std = 1.

Choose based on algorithm requirements (e.g., KNN/SVM need scaling).

Detect & Handle Outliers

Use boxplots or statistical methods (IQR/Z-score).

Decide whether to remove, cap, or transform outliers.# Task-2-Exploratory-Data-Analysis-EDA-
