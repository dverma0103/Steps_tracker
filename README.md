# Mood Prediction Using Fitness Data 🏃‍♂️📊
This project analyzes fitness tracking data to predict a person's mood based on their daily activity, including steps, sleep hours, calories burned, and active minutes. Using Logistic Regression, we achieve the best performance after preprocessing, feature selection, and model evaluation.

## 📂 Project Overview
✅ Data Preprocessing:

* Handled missing values and duplicates

* Encoded categorical variables (mood)

* Identified and removed outliers (Sleep Hours)

## ✅ Exploratory Data Analysis (EDA):

* Visualized mood distribution using bar plots

* Identified feature correlations using a heatmap

* Handled multicollinearity in highly correlated features

## ✅ Model Training & Evaluation:

* Compared Logistic Regression, Random Forest, SVM, and Gradient Boosting

* Logistic Regression performed best

* Evaluated accuracy, confusion matrix, and classification report

## ✅ Hyperparameter Tuning:

* Used GridSearchCV to optimize C and solver

* Identified important features contributing to mood prediction

# 📊 Technologies Used
🔹 Python, Pandas, NumPy, Matplotlib, Seaborn
🔹 Scikit-learn (Machine Learning)
🔹 SMOTE (for class balancing, if needed)

# 🚀 How to Run the Project
1. Clone the repository:
```
git clone https://github.com/Dverma2001/Mood-Prediction-Fitness-Data.git
cd Mood-Prediction-Fitness-Data
```
2. Install dependencies:
```
pip install -r requirements.txt
```
3. Run the Jupyter Notebook or Python script

# 📌 Results & Insights

* Happy was the most common mood

* Steps, distance, active minutes, and calories burned were highly correlated

* Logistic Regression provided the best accuracy after hyperparameter tuning

