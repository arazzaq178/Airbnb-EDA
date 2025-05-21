# Airbnb Dataset - Exploratory Data Analysis (EDA)

This project performs a complete EDA on a real-world Airbnb dataset.

## 📁 Dataset Overview
- Listings of Airbnb properties with prices, reviews, ratings, and bed details.
- Columns include: `Price`, `Offer Price`, `Review and Rating`, `Beds`, etc.

## 📊 EDA Process

### 1. Loading and Exploring Data
- Loaded using `pandas`
- Checked data types, missing values, and basic statistics

### 2. Data Cleaning
- Converted price and rating strings to numerical values
- Extracted number of beds
- Handled missing values with imputation (median) and allowed selective nulls
- Removed duplicates

### 3. Outlier Detection
- Visualized using boxplots
- Found price and review counts have high skew and outliers

### 4. Visualization
- Bar chart for bed count
- Histograms for numeric columns
- Correlation heatmap

### 5. Insights
- Most listings offer 1–4 beds
- Ratings are clustered around 4.8–5.0
- Some luxury listings act as outliers with high prices
- Weak correlation between price and review count or bed count

## 📌 Outcome
- Cleaned dataset ready for modeling or dashboarding
- Script includes visualization and preprocessing steps

## 🚀 How to Run
1. Open the `EDA_Airbnb.ipynb` or run `eda_airbnb.py`
2. Install required packages:
   ```bash
   pip install pandas matplotlib seaborn
# Airbnb-EDA
