# House Price Prediction using Machine Learning

## Project Overview

This project focuses on predicting residential property prices using Machine Learning techniques. The objective is to analyze various housing features and build predictive models that can estimate house prices accurately.

The project includes data cleaning, exploratory data analysis, feature engineering, visualization, model development, performance evaluation, and business insights.

---

## Dataset Information
**Dataset:** Housing Prices Dataset
**Source:** Kaggle
**Records:** 545
**Features:**

* Area
* Bedrooms
* Bathrooms
* Stories
* Main Road Access
* Guest Room
* Basement
* Hot Water Heating
* Air Conditioning
* Parking
* Preferred Area
* Furnishing Status

**Target Variable:**

* Price

---

## Project Workflow

### 1. Data Loading & Exploration

* Loaded dataset using Pandas
* Explored dataset structure
* Identified target and feature variables
* Checked missing values and data types

### 2. Data Cleaning

* Verified missing values
* Checked duplicate records
* Converted categorical variables using One-Hot Encoding
* Prepared dataset for machine learning

### 3. Model Building

Two regression models were developed:

#### Linear Regression

* Train-Test Split: 80:20
* Performance Metrics:

  * MAE: 970,043
  * RMSE: 1,324,507
  * R² Score: 0.653

#### Random Forest Regressor

* Performance Metrics:

  * MAE: 1,013,969
  * RMSE: 1,398,116
  * R² Score: 0.613

### Best Performing Model

Linear Regression achieved better performance across all evaluation metrics and was selected as the final model.

---

## Visualizations

### House Price Distribution

Analyzed the distribution of house prices using a histogram.

### Correlation Heatmap

Examined relationships between housing features and price.

### Actual vs Predicted Prices

Visualized model prediction performance using a scatter plot.

---

## Key Findings

* Area showed the strongest positive correlation with house price.
* Bathrooms significantly influenced property value.
* Air conditioning positively impacted pricing.
* Parking availability increased house value.
* Unfurnished houses generally had lower prices.
* Most properties were concentrated in the mid-price range.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Project Structure

```text
HousePricePrediction_SaiLikithaMadisetty/
│
├── analysis.ipynb
├── Housing.csv
├── summary.pdf
│
├── charts/
│   ├── histogram.png
│   ├── heatmap.png
│   └── scatter.png
│
└── README.md
```

---

## Conclusion

This project demonstrates the practical application of Machine Learning in the real estate domain. By leveraging housing attributes and predictive modeling techniques, it is possible to estimate property prices and identify the factors that contribute most to housing value.

---

### Author

**Sai Likitha Madisetty**

B.Tech – Artificial Intelligence & Data Science

Kandula Lakshumma Memorial College of Engineering for Women
