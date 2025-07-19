# 🌍 Global GDP Prediction Using Machine Learning

This project explores and predicts the Gross Domestic Product (GDP) of countries using historical data from 2000 to 2015. The analysis is powered by data from the World Bank and uses regression-based machine learning to forecast economic trends.

---

## 📊 Dataset

- **Source**: World Bank – [NY.GDP.MKTP.CD](https://databank.worldbank.org/indicator/NY.GDP.MKTP.CD/1ff4a498/Popular-Indicators)
- **Years Covered**: 2000 to 2015
- **Metric**: GDP in current US dollars
- **Countries**: 217
- **File**: `Data.csv`

---

## 🧠 Project Goal

To build a machine learning model that can accurately predict a country’s GDP based on its historical GDP values. The goal is to help governments, economists, and analysts estimate GDP for future planning and analysis.

---

## 📈 Exploratory Insights

- GDP ranges from **$15 million** to **$14.7 trillion**.
- Most countries show consistent GDP growth over time.
- Missing data is minimal and handled effectively.
- The dataset is right-skewed due to large economies like the U.S. and China.

---

## 🧪 Models Used

### ✅ Random Forest Regressor
- R² Score (Train): **0.950**
- R² Score (Test): **0.970**
- MAE: **$42.8B**
- RMSE: **$107.6B**

### ✅ XGBoost Regressor
- R² Score (Train): **0.9999**
- R² Score (Test): **0.9343**
- MAE: **$59.4B**
- RMSE: **$160.1B**

📌 The XGBoost model slightly overfits but still generalizes well with high accuracy.

---

## 📍 Prediction Example: India

Using GDP data from 2000 to 2014, the model predicted India's 2015 GDP:

- **Actual GDP**: `$2,103,588,360,045`
- **Predicted GDP**: `$2,033,944,231,936`
- **Absolute Error**: `$69.6B`

---

## 🧰 Tech Stack

- Python 3
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `scikit-learn`, `xgboost`, `matplotlib`, `seaborn`

---

## 📁 Repository Contents

| File/Folder         | Description                                      |
|---------------------|--------------------------------------------------|
| `Data.csv`          | Cleaned GDP dataset from the World Bank          |
| `gdp_analysis.ipynb`| Main analysis and modeling notebook              |
| `README.md`         | Project summary and documentation                |

---

## 🙏 Acknowledgements

- World Bank Open Data
- Udacity ML Nanodegree format
- Scikit-learn & XGBoost documentation

---

## 📌 License

This project is open for educational and non-commercial use. Attribution required.

