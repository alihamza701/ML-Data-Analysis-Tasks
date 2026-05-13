# Artificial Intelligence & Machine Learning Internship Developers Hub
Name : Ali Hamza Rasheed

This repository contains three mini-projects designed to build skills in **data analysis, visualization, and machine learning model development**.  
Each task demonstrates a real-world application, starting from data exploration to model training and evaluation.

---

## 📂 Project Structure

```
ai-ml-internship/
├── Task1_Data Exploration
│ ├── Code.ipynb
│
├── Task2 Stocks Prices Prediction
│ ├── Code.ipynb
|
├── Task3 Heart Disease
│ ├── Code.ipynb
│
├── README.md
```

---

## 📝 Tasks Overview

### **Task 1: Exploring and Visualizing a Simple Dataset**
**Objective:**  
Understand dataset structure and patterns using **EDA (Exploratory Data Analysis)**.

**Dataset:**  
[**Iris Dataset**](https://en.wikipedia.org/wiki/Iris_flower_data_set) (loaded via Seaborn).

**Workflow:**
1. Load dataset using `pandas` and `seaborn`.
2. Inspect shape, columns, first few rows, and statistical summary.
3. Visualize using:
   - **Scatter Plot**: Sepal Length vs Petal Length (colored by species)
   - **Histograms**: Distribution of features
   - **Box Plots**: Detect outliers
4. Libraries used: `pandas`, `matplotlib`, `seaborn`

**Example Output:**
- Identify species separation patterns.
- Spot unusual values in certain flower measurements.

---

### **Task 2: Predict Future Stock Prices (Short-Term)**
**Objective:**  
Predict the **next day's closing price** based on historical stock data.

**Dataset:**  
Stock price data from [**Yahoo Finance**](https://pypi.org/project/yfinance/) (using `yfinance` API).

**Workflow:**
1. Display a list of popular stocks for selection.
2. Download **2023 historical data**.
3. Features: `Open`, `High`, `Low`, `Volume`  
   Target: Next day's `Close`.
4. Models:
   - **Linear Regression (LR)**
   - **Random Forest Regressor (RF)**
5. Evaluate with:
   - **MSE (Mean Squared Error)**
   - **R² Score**
6. Plot **Actual vs Predicted** prices.

**Key Highlights:**
- RF model provides **feature importance**.
- Visual comparison shows prediction performance.

---

### **Task 3: Heart Disease Prediction**
**Objective:**  
Predict whether a person is at **risk of heart disease** using medical attributes.

**Dataset:**  
[**Heart Disease UCI Dataset**](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset) (CSV format).

**Workflow:**
1. Load and clean dataset (check missing values).
2. EDA:
   - Target distribution (`0` = No Disease, `1` = Disease)
3. Model:
   - Logistic Regression (max_iter=1000)
4. Evaluation Metrics:
   - **Accuracy Score**
   - **ROC Curve & AUC**
   - **Confusion Matrix**
5. Visualization:
   - Heart disease count plot
   - ROC curve
   - Confusion matrix heatmap

**Key Insights:**
- Highlights important medical factors affecting heart disease prediction.
- Demonstrates binary classification evaluation.

---

## ⚙️ Technologies Used
- **Python 3**
- **Pandas** – Data manipulation
- **Seaborn / Matplotlib** – Data visualization
- **Scikit-learn** – Machine learning models & metrics
- **yfinance** – Stock market data retrieval

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/repositoryname.git

