# 🚗 Car Price Prediction - Machine Learning Project

## 📌 Project Overview
This project focuses on predicting car prices based on various features such as brand, model, engine size, mileage, and transmission type. The dataset contains 10,000 entries with multiple numerical and categorical variables. We apply data preprocessing, exploratory data analysis (EDA), feature engineering, and machine learning models to achieve accurate price predictions.

## 📊 Steps Followed

### **1️⃣ Load & Explore the Data**
- Loaded the dataset using Pandas.
- Checked for missing values, data types, and statistical summaries.

### **2️⃣ Data Cleaning & Preprocessing**
- Ensured no missing values were present.
- Converted categorical data into numerical using **One-Hot Encoding**.
- Normalized numerical features for better model performance.

### **3️⃣ Exploratory Data Analysis (EDA)**
- Visualized the distribution of **Price, Year, Mileage, Engine Size**.
- Used **boxplots** to detect outliers.

### **4️⃣ Feature Engineering & Selection**
- Created a new feature: **Car Age = 2025 - Year**.
- Removed unnecessary columns.
- Scaled numerical data for better model efficiency.

### **5️⃣ Train Machine Learning Models**
- Implemented **Linear Regression** as a baseline model.

### **6️⃣ Model Evaluation & Prediction**
- Used **Mean Squared Error (MSE)** and **R² Score** to evaluate model performance.
- **Linear Regression Results:**
  - **MSE:** 1.578e-05
  - **R² Score:** 0.9995 (indicating excellent performance)
- Compared model accuracy and performance.

## 🛠 Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn)
- **Jupyter Notebook** for structured analysis and visualization

## 📂 Project Structure
```
📦 Car_Price_Prediction
 ┣ 📜 car_price_dataset.csv  # The dataset used for training
 ┣ 📜 cleaned_car_price_dataset.csv  # The cleaned dataset
 ┣ 📜 Car_price.ipynb  # Jupyter Notebook with the analysis & models
 ┣ 📜 README.md  # Project documentation
```

## 🚀 Ho
## 📌 Future Improvements
- Try more complex models like **Neural Networks**.
- Implement **Feature Selection** to reduce redundant data.
- Improve **Hyperparameter Tuning** for better accuracy.

---
### 🏆 Author: Nassim BENCHIKH
✅ **GitHub:** [Your Profile Link]
✅ **LinkedIn:** [Your Profile Link]
