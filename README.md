# Stock Price Prediction with Machine Learning

Welcome to the **Stock Price Prediction** project! This repository demonstrates how to use machine learning techniques to analyze and predict stock prices, using Tesla's historical stock data as a case study.

## Project Overview

- **Data Source:** The dataset (`Tesla.csv`) contains historical stock prices for Tesla, Inc., including columns for Date, Open, High, Low, Close, Volume, and Adjusted Close.
- **Notebook:** The main analysis is performed in `Stock_Price_Prediction.ipynb`, a Jupyter Notebook that walks through data exploration, visualization, preprocessing, and predictive modeling.

## Features

- 📈 **Data Exploration & Visualization:**
  - Uses `pandas`, `matplotlib`, and `seaborn` to explore and visualize trends in Tesla's stock prices.
- 🤖 **Machine Learning Models:**
  - Implements Logistic Regression, Support Vector Classifier (SVC), and XGBoost Classifier for stock price prediction.
  - Utilizes `scikit-learn` for model training, evaluation, and preprocessing.
- 🧹 **Data Preprocessing:**
  - Handles missing values, feature scaling, and train-test splitting.
- 📊 **Performance Metrics:**
  - Evaluates models using accuracy and other relevant metrics.

## Getting Started

### Prerequisites
- Python 3.7+
- Jupyter Notebook
- Required Python packages:
  - numpy
  - pandas
  - matplotlib
  - seaborn
  - scikit-learn
  - xgboost

Install dependencies with:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
```

### Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/stock-price-prediction.git
   cd stock-price-prediction
   ```
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook Stock_Price_Prediction.ipynb
   ```
3. Follow the notebook cells to explore the data and run the machine learning models.

## File Structure
- `Stock_Price_Prediction.ipynb` — Main notebook for data analysis and modeling
- `Tesla.csv` — Historical stock price data for Tesla
- `.gitignore` — Specifies files and folders to be ignored by git

## License
This project is for educational purposes only.

---

*Crafted with ❤️ for data science and machine learning enthusiasts!*