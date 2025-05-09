#  BMI Sentiment Analysis & Classification

This project aims to predict a person's **health index category (Index)** based on biometric data such as gender, height, weight, and **BMI**, using machine learning techniques — notably **AutoGluon**.

---

##  Project Files

- `BMI.csv` — Dataset containing the columns: `Gender`, `Height`, `Weight`, and `Index`.
- `bmi_sentiment_analysis.ipynb` — Main notebook including data analysis, modeling, and predictions.

---

##  Tools & Libraries

- Python 3.10+
- pandas, numpy
- seaborn, matplotlib
- scikit-learn
- AutoGluon

---

##  Project Steps

### 1. Data Loading & Cleaning
- Check for missing values
- Encode the `Gender` column
- Create a new `BMI` column

### 2. Exploratory Data Analysis
- Boxplots to visualize feature distribution
- Correlation matrix to explore relationships

### 3. Data Preparation
- Split dataset into training and testing sets
- Separate features (`X`) and target (`y`)

### 4. Model Training with AutoGluon
- Use `TabularPredictor` for automatic model training
- Evaluate performance on test data

### 5. Prediction
- Predict health index categories and probabilities on new biometric entries

---

##  Example: Making Predictions

```python
new_df = pd.DataFrame({
    'Gender': [1, 0],
    'Height': [175, 160],
    'Weight': [70, 55],
    'BMI': [22.86, 21.48]
})

# Predictions
predictor.predict(new_df)
predictor.predict_proba(new_df)
```

---

##  Expected Output

- A predicted **Index class** for each new individual
- The **associated probabilities** for each possible class

---

##  Notes

- AutoGluon automates model selection and hyperparameter tuning.
- This project is well-suited for educational purposes or a demo prototype in **pattern recognition**.

---

##  Author

Priscille Ebwala  
Master 2 – Systèmes Intelligents & Multimédia  
Université Nationale du Vietnam – IFI  
 ebwalette@gmail.com

 This project was conducted as part of a practical session in the *Pattern Recognition* course.
