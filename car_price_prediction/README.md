# 🚗 Car Price Prediction

## 📌 Overview
This project predicts car prices based on various features such as **mileage, make, model, engine specifications, and more**. The dataset undergoes **preprocessing, exploratory data analysis (EDA), feature engineering**, and is trained using **Linear Regression**. The goal is to build a predictive model that provides accurate price estimations based on given car attributes.

## 📊 Features

### **1️⃣ Data Preprocessing**
- **Dropping Non-Useful Columns**: Removed features that do not contribute significantly to price prediction.
- **Feature Scaling**: Used **StandardScaler** to normalize numerical features.
- **One-Hot Encoding**: Converted categorical variables (**Make, Model, Type**) into binary columns.

### **2️⃣ Exploratory Data Analysis (EDA)**
- **Visualizing Data Distributions**
  - Kernel Density Estimation (KDE) plots for **Price** and **Mileage**.
  - Bar charts for **Car Brands, Models, and Types**.
  - Pie charts for **Doors, Cruise Control, Sound System, Leather Seats, Cylinder Count, and Engine Liter**.
  

### **3️⃣ Machine Learning**
- **Data Splitting**: Split dataset into **training (70%)** and **testing (30%)** sets.
- **Training the Model**: Implemented **Linear Regression**.
- **Evaluation Metrics**:
  - **Mean Squared Error (MSE)**
  - **Root Mean Squared Error (RMSE)**
  - **Mean Absolute Error (MAE)**
  - **R-squared Score (R²)**

---

