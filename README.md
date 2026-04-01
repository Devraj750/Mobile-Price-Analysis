# 📱 Mobile Price Analysis & Prediction

## 🚀 Project Overview
This project focuses on analyzing mobile phone features and understanding how different attributes influence the price range of mobile devices.

The goal is to explore relationships between features like RAM, battery power, camera quality, and connectivity (3G/4G/Bluetooth) with the price category of mobile phones.

## 📊 Dataset Information
- Dataset Source: [Kaggle - Mobile Price Classification]
- Total Features: 20+
- Target Variable: `price_range`
- Data Type: Structured Tabular Data

## 🎯 Objectives
- Perform **Exploratory Data Analysis (EDA)**
- Identify **key features impacting mobile prices**
- Visualize feature relationships using graphs
- Understand trends in mobile specifications

## 🛠️ Tech Stack
- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔍 Key Steps Performed

### 1. Data Loading & Inspection
- Loaded dataset using Pandas
- Checked shape, columns, and data types
- Verified missing values (No null values found ✅)

### 2. Data Cleaning & Transformation
- Renamed columns for better readability
- Converted categorical values (0 → No, 1 → Yes)
- Structured dataset for analysis

### 3. Exploratory Data Analysis (EDA)
- Statistical summary using `.describe()`
- Correlation heatmap to identify relationships
- Count plots for categorical features

### 4. Data Visualization
- 📈 Heatmap for correlation analysis
- 📊 Count plots for:
- 3G availability
- 4G availability
- Bluetooth support

## 📌 Key Insights

- 📷 **Camera features (fc, px_height, px_width)** have strong impact on price
- 📱 **Screen dimensions (sc_h, sc_w)** also influence pricing
- 📡 Most phones support **3G**, while 4G adoption is moderate
- 🔵 Bluetooth is common across all price ranges

## 💡 Learning Outcomes
- Hands-on experience with real-world dataset
- Improved data cleaning & visualization skills
- Better understanding of feature correlation
- Writing reusable functions for plotting

## 🔗 Future Improvements
- Build ML model for price prediction
- Deploy using Streamlit
- Add feature importance ranking

## 🙌 Conclusion
This project provides valuable insights into mobile pricing factors and builds a strong foundation for future machine learning models.

## ⭐ If you like this project
Give it a ⭐ on GitHub and share your feedback!
