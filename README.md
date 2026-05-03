# 📊 Insurance Charges Predictor

## 🚀 Overview

This project is a complete **Machine Learning pipeline** that predicts **medical insurance charges 💰** based on user attributes like age, BMI, smoking status, and region.

It includes **EDA, preprocessing, feature engineering, statistical testing, and model building** — making it a strong end-to-end ML project.

---

## ✨ Features

* 📊 Exploratory Data Analysis (EDA)
* 🧹 Data Cleaning & Preprocessing
* 🧠 Feature Engineering (BMI categories, encoding)
* 📈 Statistical Analysis (Pearson & Chi-Square)
* ⚙️ Feature Scaling (StandardScaler)
* 🤖 Linear Regression Model
* 📉 Model Evaluation (R² & Adjusted R²)

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Seaborn, Matplotlib
* Scikit-learn
* SciPy

---

## 📂 Dataset

* Dataset: `insurance.csv`
* Contains:

  * Age
  * Sex
  * BMI
  * Children
  * Smoker status
  * Region
  * Charges (target)

---

## ⚙️ Project Workflow

### 1. Data Understanding

* Shape, data types, summary statistics
* Missing value analysis

### 2. Exploratory Data Analysis

* Distribution plots (histograms)
* Count plots (categorical features)
* Boxplots (outlier detection)
* Correlation heatmap

---

### 3. Data Preprocessing

* Remove duplicates
* Encode categorical variables:

  * Sex → binary
  * Smoker → binary
* One-hot encoding for region
* Rename columns for clarity

---

### 4. Feature Engineering

* Created BMI categories:

  * Underweight
  * Normal
  * Overweight
  * Obese
* Converted into dummy variables

---

### 5. Feature Scaling

* StandardScaler applied on:

  * Age
  * BMI
  * Children

---

### 6. Statistical Analysis

#### 📌 Pearson Correlation

* Measures linear relationship with target (charges)

#### 📌 Chi-Square Test

* Evaluates importance of categorical features

---

### 7. Model Building

* Algorithm: **Linear Regression**
* Train-test split: 80-20

---

### 8. Model Evaluation

* R² Score
* Adjusted R² Score

---

## ▶️ How to Run

### 1. Install dependencies

```bash id="p2k9vs"
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

### 2. Run the script

```bash id="p5u9lb"
python INSURANCE PREDICTOR.py
```

---

## 📊 Results

* Model achieves a good **R² score**
* Adjusted R² used for better reliability
* Smoking status and BMI show strong influence on charges

---

## 📈 Key Insights

* 🚬 Smokers have significantly higher insurance costs
* ⚖️ BMI strongly impacts charges
* 👶 Number of children has moderate impact
* 🌍 Region has smaller influence compared to health factors

---

## 🚀 Future Improvements

* Try advanced models (Random Forest, XGBoost)
* Build a web app (Streamlit)
* Add real-time prediction UI
* Hyperparameter tuning
* Deploy as API

---

## 👨‍💻 Author

Built as a complete ML project demonstrating:

* Data analysis
* Feature engineering
* Statistical testing
* Model building

---

## ⭐ If you like this project

Give it a star ⭐ on GitHub!
