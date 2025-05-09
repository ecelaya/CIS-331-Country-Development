# 🌍 CIS 331 Project – Analysis of Economic and Social Indicators Across Countries

This project was developed as part of the CIS 331 course (Winter 2025) and focuses on analyzing key development indicators across countries using data from the World Bank. The objective is to understand the relationships between health, education, economic indicators, and overall development outcomes such as life expectancy.

## 📊 Project Overview

The analysis includes:

- **Data Cleaning & Transformation**: Preprocessed the World Bank dataset, handled missing values, reshaped the data for usability, and added region/categorical variables.
- **Exploratory Data Analysis (EDA)**: Performed univariate and bivariate analysis, applied transformations to address skewness, and visualized key relationships between indicators.
- **Clustering (Unsupervised Learning)**: Applied K-Means clustering to group countries based on GDP per capita, life expectancy, and water access.
- **Regression (Supervised Learning)**: Built a linear regression model to predict life expectancy based on several development indicators.
- **Classification (Supervised Learning)**: Used Decision Tree and K-Nearest Neighbors (KNN) to classify countries into income groups.

## 📁 Files

- `CIS_331_PROJECT.ipynb`: The full analysis code in Jupyter Notebook format.
- `CIS 331 REPORT.pdf`: A comprehensive report with explanations, visualizations, and results.
- - `world_bank_cleaned_dataset.csv` – Cleaned dataset used for modeling
- `3D_Cluster_Plot.html` – Interactive 3D K-Means visualization

## 🔧 Technologies Used

- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Jupyter Notebook

## 🌐 Data Source

- [World Bank – World Development Indicators](https://databank.worldbank.org/source/world-development-indicators)

## 📌 Key Insights

- **GDP per capita and Life Expectancy** are strongly positively correlated.
- Countries can be grouped into 4 meaningful development clusters using unsupervised learning.
- Decision Trees outperformed KNN in income group classification, achieving 93% test accuracy.

---

📍 *Author: Eloy Celaya López*  
📅 *Course: CIS 331 – Winter 2025*
