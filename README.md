# 🏠 Housing Price Prediction - Linear Regression

This project is part of my internship at **Elevate Labs**, where I implemented both **Simple and Multiple Linear Regression** using the **Housing Price Prediction Dataset**.

## 📌 Objective
To build and evaluate a Linear Regression model to predict house prices using features like area, bedrooms, bathrooms, and more.

## 📁 Dataset
- Source: [Kaggle - Housing Price Prediction Dataset](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)
- Format: CSV
- Target Variable: `price`

## 🛠️ Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## ✅ Steps Followed

1. **Data Import & Exploration**
   - Loaded the dataset using `pandas`
   - Checked for nulls and types of features

2. **Data Preprocessing**
   - Converted categorical columns to numerical using mapping and one-hot encoding
   - Scaled/normalized if required (not necessary for Linear Regression here)

3. **Train-Test Split**
   - Used `train_test_split` to split dataset into 80% training and 20% testing

4. **Model Training**
   - Applied `LinearRegression()` from `sklearn.linear_model`

5. **Evaluation Metrics**
   - MAE (Mean Absolute Error)
   - MSE (Mean Squared Error)
   - R² Score

6. **Visualization**
   - Plotted regression line vs actual data (for simple regression)
   - Plotted residuals for model diagnostics

7. **Model Interpretation**
   - Displayed model coefficients
   - Interpreted effect of features on target variable

## 📊 Results

| Metric | Value |
|--------|-------|
| MAE    | *value_here* |
| MSE    | *value_here* |
| R²     | *value_here* |

(Replace values with your actual model results)

## 📌 Key Learnings
- Understood how to apply and interpret linear regression
- Learned how to evaluate a regression model using various metrics
- Explored real-world data preprocessing and feature encoding

## 📝 Interview Questions Prepared
- Assumptions of Linear Regression
- When to use MSE vs MAE
- Difference between simple and multiple regression
- Use of R² score
- Detecting multicollinearity
- Can Linear Regression be used for classification?

## 📷 Screenshots

*(Include screenshots of code output/graphs if required)*

## 🔗 Submission
Submitted via the official form: [Google Form Link](https://forms.gle/8Gm83s53KbyXs3Ne9)

---

### ✨ Thank you Elevate Labs for this learning opportunity!
