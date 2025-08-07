# 🎮 Video Game Hardware Sales Prediction in Python

Welcome to the **Video Game Hardware Sales Prediction** project!  
This project focuses on predicting the sales performance of video game hardware using historical data and machine learning models, entirely implemented in Python.

![Gaming Banner](https://drive.google.com/uc?id=1jITB8WBfBAP9sh1XjLb4wFvHr8zjnhc5)

---

## 📌 Table of Contents

- [Project Description](#project-description)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Notebook Overview](#notebook-overview)
- [Modeling Process](#modeling-process)
- [Results](#results)
- [How to Run](#how-to-run)
- [Screenshots](#screenshots)
- [License](#license)
- [Author](#author)

---

## 📝 Project Description

This project aims to forecast the global sales of video game hardware based on historical trends. It explores data preprocessing, visualization, and the use of machine learning models to provide insights into sales dynamics across regions.

---

## 📊 Dataset

The dataset used is sourced from publicly available game sales data repositories. It contains:

- **Platform** (e.g., Wii, PS2, etc.)
- **Year of Release**
- **Units Sold Globally**
- **Regional Sales** (North America, Europe, Japan, Others)

📁 Dataset is embedded within the notebook or can be imported via CSV if needed.

---

## 🧰 Technologies Used

- Python 3.x
- Jupyter Notebook
- pandas
- matplotlib / seaborn
- scikit-learn
- numpy
- plotly (optional for advanced visualization)

---

## 📒 Notebook Overview

The notebook covers:

1. **Data Import & Exploration**  
   - Load data  
   - Check null values  
   - Inspect distributions

2. **Data Cleaning**  
   - Handle missing values  
   - Convert data types

3. **Visualization**  
   - Bar charts  
   - Pie charts  
   - Heatmaps

4. **Feature Engineering**  
   - One-hot encoding  
   - Normalization

5. **Modeling**  
   - Train/Test Split  
   - Linear Regression  
   - Decision Tree / Random Forest  
   - Model evaluation using RMSE / R²

6. **Prediction**  
   - Predict global hardware sales for specific platforms

---

## 🧪 Modeling Process

Several regression models were tested, including:

- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**

The performance was evaluated using metrics like:

- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score**

📈 The model with the best performance was selected based on RMSE and visualization of residuals.

---

## 📌 Results

- Models achieved decent performance in predicting sales trends.
- Visualization gave insight into which platforms dominated the market historically.
- Regional differences in sales were highlighted and interpreted.

---

## ▶️ How to Run

To run this notebook locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/airulhafiq/Video-Game-Hardware-Sales-Prediction.git
   cd Video-Game-Hardware-Sales-Prediction

2. Open the notebook:

   ```bash
   jupyter notebook Video_Game_Hardware_Sales_Prediction_in_Python.ipynb
   ```

## 🙋‍♂️ Author

Developed by **Airul Hafiq**
📧 [Contact Me on LinkedIn](https://www.linkedin.com/in/airulhafiq/)
🧠 AI Enthusiast

---

⭐ If you find this project useful, don't forget to star the repository and share it with others!
