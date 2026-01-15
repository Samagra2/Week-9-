# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview
This project demonstrates the implementation of **machine learning fundamentals** by building a **house price prediction model** using real-world data. The goal is to predict house prices based on features such as **area, bedrooms, bathrooms, age, location, and property type**, and to evaluate multiple regression models.

This project is designed as part of **Week 9: Introduction to Machine Learning Concepts** and is suitable for **academic submission, internships, and portfolio showcase**.

---

## 🎯 Objectives
- Understand the basics of machine learning
- Implement **Linear Regression** from scratch (conceptual)
- Build regression models using **scikit-learn**
- Apply proper **train–test split**
- Evaluate models using standard metrics
- Visualize **predicted vs actual values**
- Compare multiple regression algorithms

---

## 📂 Dataset
**File:** `house_prices.csv`  
**Rows:** 300  
**Features:**
- `Area`
- `Bedrooms`
- `Bathrooms`
- `Age`
- `Location` (categorical)
- `Property_Type` (categorical)
- `Price` (target variable)

---

## 🛠️ Technologies & Tools Used
- Python
- Google Colab
- Pandas & NumPy
- Matplotlib
- Scikit-learn

---

## 📁 Project Structure
house-price-prediction/
│
├── house_price_prediction.ipynb
├── house_prices.csv
├── predictions_vs_actual.png
├── model_evaluation_report.md
├── requirements.txt
└── README.md


---

## 🔍 Machine Learning Workflow
1. Data loading and exploration  
2. Data cleaning and preprocessing  
3. Feature and target selection  
4. Train–test split  
5. Model training  
6. Model evaluation  
7. Visualization and interpretation  

---

## 🤖 Models Implemented
- Linear Regression (from scratch – numeric features)
- Linear Regression (scikit-learn)
- Polynomial Regression
- Decision Tree Regressor
- Random Forest Regressor

---

## 📊 Model Evaluation Metrics
The following evaluation metrics were used:

- **MAE (Mean Absolute Error)**
- **MSE (Mean Squared Error)**
- **R² Score**

### Best Model Performance
| Model | R² Score |
|------|----------|
| Linear Regression | 0.94 |
| Polynomial Regression | 1.00 |
| Decision Tree | 0.94 |
| Random Forest | **0.97** |

---

## 📈 Visualization
### Predictions vs Actual Prices
The model performance is visualized using a scatter plot comparing actual house prices with predicted values.

**File Generated:**  
`predictions_vs_actual.png`

---

## 💡 Key Insights
- Property **area** is the most influential feature in price prediction
- Linear Regression provides a strong baseline
- Random Forest captures non-linear relationships effectively
- Proper encoding of categorical variables improves model accuracy

---

## 🚀 How to Run the Project
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
