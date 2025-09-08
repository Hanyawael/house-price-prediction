

# 🏡 Housing Price Prediction

## 📌 Overview

This project focuses on predicting **California housing prices** using **Linear Regression**.
The dataset includes demographic, geographical, and housing-related features such as total rooms, bedrooms, households, population, and proximity to the ocean.

---

## ⚙️ Project Workflow

* **Data Cleaning**: Handling missing values.
* **Feature Engineering**: Creating additional features like:

  * Rooms per household
  * Bedrooms per room
  * Population per household
* **Encoding**: One-hot encoding for categorical variables (`ocean_proximity`).
* **Train/Test Split**: Dividing the dataset into 80% training and 20% testing.
* **Model Training**: Applying Linear Regression with scikit-learn.
* **Evaluation**: Measuring performance using MSE, RMSE, and R² Score.

---

## 📈 Results

* The model provides a reasonable prediction of housing prices.
* Performance evaluation shows the effectiveness of Linear Regression in capturing trends.

---

## 🚀 Future Improvements

* Normalize and scale features for better performance.
* Try **Polynomial Regression** to capture non-linear relationships.
* Experiment with advanced models like **Random Forest** or **XGBoost** for higher accuracy.

---

## 👩‍💻 Tech Stack

* **Python**
* **Pandas & NumPy**
* **Scikit-learn**
* **Matplotlib & Seaborn**
