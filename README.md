# 📊 Capstone Project: Menu Sales Forecasting

## 🧩 Problem Statement
The goal of this project is to support better decision-making for a restaurant by analyzing past sales data. By identifying high-revenue items and recognizing trends based on quantity and time, we aimed to build a system to forecast future sales. This allows the business to manage inventory efficiently, reduce waste, and ensure popular items are always available.

## 📂 Data Acquisition
We used a complete transaction dataset from 2023 to 2025, which included:
- Order dates
- Item names
- Quantities sold
- Net prices

This dataset helped us uncover revenue patterns, seasonal spikes, and top-selling items critical for business forecasting and strategy.

## 🧼 Data Preparation
To prepare the data for machine learning:
- Voided (canceled) transactions were removed
- Price fields were cleaned and converted to numeric
- New time-based features like **Month** and **Year** were extracted
- The dataset was split into training and testing sets for model validation

## 📈 Exploratory Analysis
Visualizations were created to explore:
- Top 10 selling items
- Monthly and daily seasonal trends
- Revenue contributions by item

These insights guided the modeling approach and supported future planning.

## 🤖 Modeling
We used two regression models to predict future item-level revenue:
- **Linear Regression** – effective for identifying basic linear trends
- **Random Forest** – more advanced, capable of capturing nonlinear patterns and interactions

## 📊 Model Evaluation
We measured model performance using:
- **R² Score**: to show how much variance is explained by the model
- **Mean Squared Error (MSE)**: to measure prediction error

The **Random Forest model** outperformed Linear Regression in both metrics and is recommended for ongoing revenue forecasting tasks.

## ✅ Results & Recommendation
- Random Forest provided stronger and more accurate predictions
- Revenue predictions can improve inventory decisions and reduce waste
- Future enhancements can include additional data features (e.g., time of day, promotions, location)

## 📁 Files Included
- `Capstone_Project_Final.ipynb
- `Capstone Project_Final.docx
- Capstone_Project-Menu_Sales_Summary_Presentation.pptx
- `README.md
