# House_Prices_EDA

# House Price Exploratory Data Analysis (EDA)

## Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on a House Price dataset to understand the factors that influence house prices.

The main goal is to explore the dataset, identify patterns and relationships, detect outliers, and understand the quality of the data before building a machine learning model.

##  Objectives

- Understand the distribution of house prices.
- Identify the most important features affecting house prices.
- Analyze house prices across different neighborhoods.
- Detect outliers using statistical methods.
- Handle and understand missing values.
- Visualize relationships between different features.

## 📂 Project Structure

```text
House-Price-EDA/
│
├── EDA_House_Price_Analysis.ipynb
├── README.md
├── house_price_distribution.png
├── correlation_heatmap.png
├── neighborhood_prices.png
└── outlier_analysis.png
```

##  Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

##  Exploratory Data Analysis

### 1 SalePrice Distribution

Analyzed the distribution of house prices using histograms and statistical measures.

- The distribution is right-skewed.
- Most houses are priced below $200,000.
- The mean price is approximately $180,900.
- The median price is approximately $163,000.

### 2.Feature Correlation

Studied the relationship between house prices and different features.

The most strongly correlated features with `SalePrice` were:

| Feature | Correlation |
|---|---:|
| OverallQual | 0.79 |
| GrLivArea | 0.71 |

Overall quality and living area showed strong positive relationships with house prices.

### 3.Neighborhood Analysis

Compared average house prices across different neighborhoods.

- `NoRidge` and `NridgHt` had average prices above $300,000.
- House prices varied significantly across neighborhoods.

### 4. Outlier Detection

Used two statistical methods to identify unusual data points:

- Interquartile Range (IQR)
- Z-score

The IQR method identified 31 outliers in living area, while the Z-score method identified 16.

Some houses had very large living areas but surprisingly low sale prices.

### 5. Missing Value Analysis

Identified columns with a high percentage of missing values, including:

- `PoolQC`
- `MiscFeature`
- `Alley`

These missing values often indicate the absence of a feature rather than incorrect data.

## Key Insights

- House quality is one of the strongest factors associated with house prices.
- Larger living areas generally correspond to higher house prices.
- Neighborhood plays an important role in determining house prices.
- Outliers can affect statistical analysis.
- Missing values should be understood before handling them.

##  Limitations

- The analysis mainly focuses on linear relationships.
- Complex interactions between features were not explored.
- Outliers may affect correlation and other statistical measures.
- No machine learning model was developed in this project.




## 👩‍💻 Author

**Anjali Tiwari**

BTech – Computer Science & Information Technology


