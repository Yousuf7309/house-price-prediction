# 🏠 House Price Prediction (Ames Housing Dataset)

This project uses machine learning models to predict house sale prices based on the popular Ames Housing dataset. It demonstrates a complete end-to-end data science workflow from preprocessing and feature engineering to model evaluation and final predictions.

---

## 📌 Project Description

The goal of this project is to build a regression model that accurately predicts the sale price of houses using various features like neighborhood, house style, lot area, and more. This is a classic supervised regression problem and is commonly used for learning feature engineering, model training, and evaluation in real-world scenarios.

---

## 📊 Dataset Description

The dataset includes detailed information on residential homes in Ames, Iowa. Features include:

- **MSSubClass**: Type of dwelling
- **LotFrontage**: Linear feet of street connected to property
- **Neighborhood**: Physical location within Ames
- **OverallQual**: Overall material and finish of the house
- **YearBuilt**, **GarageType**, **SaleCondition**, and many more

The full list of columns and descriptions is included in the notebook.

---

## ✅ Key Tasks Completed

- Data cleaning and missing value treatment
- Outlier detection and handling
- Categorical and numerical feature encoding
- Feature scaling using StandardScaler
- Model training with Linear Regression and Random Forest
- Model evaluation using RMSE and R² score
- Final predictions on test dataset

---

## 🧪 Model Performance

- **Linear Regression RMSE**: ~22,500
- **Linear Regression R²**: ~0.89
- **Random Forest RMSE**: ~19,804
- **Random Forest R²**: ~0.91

---

## 📁 File Structure

```
house-price-prediction/
├── README.md
├── data/
│   └── train.csv
│   └── test.csv
│   └── test_with_predictions.xlsx
├── notebook/
│   └── House_Price_Prediction.ipynb
│   └── requirements.txt
```

---

## 🧠 How to Run

1. Clone the repository
2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook notebook/house_price_prediction.ipynb
```

4. Run all cells

---

## 📦 Requirements

See `requirements.txt` for all required Python libraries.

---

## ✍️ Author

**Mohammad Yousuf**  
🔗 [LinkedIn](https://www.linkedin.com/in/yousufmohammed-989aaa1b8/)
---

## 📜 License

This project is for educational purposes.
