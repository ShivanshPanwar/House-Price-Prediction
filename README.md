💬 **House Price Prediction**

A Python-based machine learning project to predict housing prices using regression techniques. Built in Google Colab, this project demonstrates data preprocessing, exploratory data analysis, feature engineering, model building, and evaluation. Users can input property features such as area, bedrooms, bathrooms, and location to predict house prices.

**Table of Contents**

1.Project Overview
2.Dataset
3.Features
4.Modeling Approach
5.Requirements
6.Installation & Setup
7.Results
8.Future Improvements

**Project Overview**

This project aims to predict housing prices based on various factors such as location, area, and property features. Using Multiple Linear Regression, the project follows a structured workflow:

• Data cleaning and preprocessing
• Exploratory Data Analysis (EDA)
• Feature selection and engineering
• Model building and evaluation

**Dataset**
The dataset contains historical house prices along with relevant property features.

**File:** Housing.csv

**Key Columns:**
area – size of the property in sq.ft
bedrooms – Number of bedrooms
bathrooms – Number of bathrooms
location – Geographic location of the property
price – Target variable (house price)

🚀 **Features**

• Data Preprocessing – Handles missing values, encoding, and scaling of features.
• Exploratory Data Analysis – Visualizations and correlation analysis to understand dataset trends.
• Multiple Linear Regression – Predicts house prices using regression models.
• Performance Evaluation – RMSE and R² metrics for model accuracy.
• Visualization – Scatter plots, heatmaps, and distribution plots to analyze features and target.
• User Input Prediction – Predict prices for new property data points.
• Scalable – Can be extended to advanced regression models like Random Forest or XGBoost.

**Modeling Approach**

**Algorithm Used:** Multiple Linear Regression

**Libraries Used**: pandas, numpy, scikit-learn, matplotlib, seaborn

**Evaluation Metrics:**

•Root Mean Squared Error (RMSE)
•R² Score

**Performance:**

| Dataset  | RMSE         | R² Score |
| -------- | ------------ | -------- |
| Training | 1,046,377.40 | 0        |
| Testing  | 1,041,399.17 | 0        |

💻 **Requirements**

• Python 3.8 or above
• Google Colab (or local Python environment)
• Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

⚙️ **Installation & Setup**

1. Clone the repository:
git clone https://github.com/ShivanshPanwar/House-Price-Prediction.git

2. Navigate to the project folder:
cd House-Price-Prediction

3. Install dependencies:
pip install -r requirements.txt

4.Open the notebook in Google Colab: HousePricePrediction.ipynb

5.Run all cells sequentially to execute the workflow and make predictions.

📈 **Results**

The model predicts house prices based on input features with reasonable accuracy. Visualizations include correlation heatmaps, scatter plots, and feature distribution plots. Performance metrics on training and testing sets are recorded as RMSE and R² scores.

⚙️ **Future Improvements**

• Implement advanced regression techniques such as Random Forest or XGBoost.
• Improve feature engineering and handle missing values more effectively.
• Deploy as a web application for real-time price predictions.
• Include automated hyperparameter tuning to enhance model performance.
