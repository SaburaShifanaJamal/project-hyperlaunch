# project-hyperlaunch

# Flipkart Mobile Price Prediction 📱📊

This project involves data analysis and machine learning modeling to predict the selling price of mobile phones listed on Flipkart. The core objective is to build a regression model that estimates mobile prices based on features like RAM, ROM, brand, camera specs, ratings, and more.

## 🧠 Project Highlights

- 📌 Data cleaning and preprocessing
- 📈 Exploratory Data Analysis (EDA)
- 🔄 Feature encoding and transformation
- 🌲 Random Forest Regression modeling
- 📊 Evaluation using regression metrics (MAE, MSE, RMSE, R²)

## 📂 Dataset
Source : Kaggle - https://www.kaggle.com/
- The dataset contains features like:
- Brand
- RAM, ROM
- Ratings
- original price
- Final selling price (target variable)

## 🧪 Libraries Used

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`

##  Model Used

- **Random Forest Regressor**
  - Default and tuned hyperparameters
  - Trained and tested on cleaned dataset
  - Performance evaluated with standard regression metrics

##  Results

The model gave good predictive performance with:
- **Mean Squared Error**:11369545.858158827
- **R² Score**:  0.9841410060972354
    This indicates that about 98.4% of the variance in the selling price is explained by the model, showing excellent predictive accuracy.
##  How to Run

1. Clone the repository
2. Make sure you have Python and Jupyter installed
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
