# 🍽️ Restaurant Tip Prediction Analysis

## 📊 Project Overview
This project analyzes restaurant tipping patterns using exploratory data analysis (EDA) and machine learning. The goal is to predict tip percentages based on various factors like party size, time of day, and customer demographics.

## 📁 Files
- `restaurant_tip.py` - Main analysis script with data loading, EDA, feature engineering, and model training

## 🔍 Key Features

### Data Processing
- Load and validate tip dataset (244 rows)
- Calculate tip percentage from bill and tip amount
- Handle missing values and data types

### Exploratory Data Analysis
- Outlier detection using IQR method
- Visualization of tip patterns by:
  - Party size
  - Customer sex
  - Smoking status
  - Time of day (lunch/dinner)

### Feature Engineering
- Create tip_percentage feature
- One-hot encode categorical variables (sex, smoker, day, time)

### Machine Learning
- Train Random Forest Regressor
- Feature importance analysis
- Model evaluation with R² and RMSE metrics

## 📈 Key Insights
- **Tipping Patterns:** Lunch time women give higher tips, while dinner time men are more generous tippers
- **Smoker Behavior:** Smokers tend to give higher tips overall compared to non-smokers
- **Model Limitations:** While the current features provide some predictive power, they are not sufficient to predict a fully satisfactory tipping pattern, suggesting additional factors beyond demographics and time influence tipping behavior
- Outlier detection identifies unusually high tipping percentages
- Feature correlations reveal which factors most influence tipping behavior

## 🛠️ Requirements
```
pandas
numpy
seaborn
matplotlib
scikit-learn
```

## 📊 Model Performance
- **Metric:** R² Score and RMSE (Root Mean Squared Error)
- **Train/Test Split:** 80/20 ratio

## 👤 Author
Yeabsira Belete Mamo