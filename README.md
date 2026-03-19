# 🌊 SONAR Rock vs Mine Prediction System

A Machine Learning model that classifies underwater objects as either **Rocks** or **Mines (Metal Cylinders)** using SONAR data. This project is designed to enhance submarine navigation and underwater safety by automating object detection.

## 🚀 Overview
The system uses sonar signals reflected off underwater objects. Each signal consists of 60 different frequency bands, which serve as features for our classification model.

- **Objective:** Distinguish between harmless rocks and explosive mines.
- **Algorithm:** Logistic Regression (Binary Classification).
- **Dataset:** UCI Machine Learning Repository - Sonar Dataset.

## 📊 Visualizations

| Feature Correlation Heatmap | Model Performance (Confusion Matrix) |
| :---: | :---: |
| ![Heatmap](https://github.com) | ![Confusion Matrix](https://github.com) |

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** NumPy, Pandas, Scikit-learn
- **Environment:** Jupyter Notebook / Google Colab

## 📈 Model Performance
- **Training Accuracy:** ~83%
- **Testing Accuracy:** ~76%
*(Update these with your actual results!)*

## ⚙️ How to Run
1. Clone the repo: `git clone https://github.com`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebook: `jupyter notebook Rock_vs_Mine.ipynb`
