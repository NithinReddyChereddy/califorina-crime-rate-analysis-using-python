# 📊 California Crime Rate Analysis (2000–2013)

This data science project explores violent crime trends in California across a 14-year span using Python. The analysis focuses on understanding crime distribution by region, year, and type while applying machine learning to predict future crime rates.

---

## 🧠 Objectives

1. **Data Cleaning** – Handle missing values, standardize data, filter relevant rows.
2. **Exploratory Data Analysis (EDA)** – Visualize trends, detect outliers, and identify hotspots.
3. **Advanced Visualization** – Create heatmaps, line plots, and comparative charts.
4. **Statistical Analysis** – Apply hypothesis testing (T-test, ANOVA, Kruskal-Wallis).
5. **Predictive Modeling** – Train a regression model to forecast future crime rates.

---

## 📁 Project Structure


---

## 🔧 Technologies Used

- **Python 3.x**
- **Pandas** – data handling
- **NumPy** – numerical operations
- **Matplotlib** / **Seaborn** – visualization
- **Scikit-learn** – ML modeling
- **SciPy** / **Statsmodels** – statistical tests
- **Joblib** – model serialization

---

## 📈 Key Insights

- Alameda had the highest average violent crime rate.
- Crime rates in California showed a gradual decline after 2005.
- Urban areas experienced significantly higher crime rates than rural ones.
- Predictive modeling suggests the trend may continue declining in the near future.

---

## 🧪 Statistical Tests

- **Shapiro-Wilk Test** – Normality check
- **T-Test** – Urban vs Rural comparison
- **ANOVA / Kruskal-Wallis** – Crime differences across years

---

## 🔮 Machine Learning

- **Model:** Linear Regression
- **Target Variable:** Crime Rate (`rate`)
- **Feature Used:** Report Year (`reportyear`)
- **Model File:** `crime_predictor.pkl`
- **Prediction Example:** Forecasted crime rate for 2024

---

## 📌 How to Run

1. Clone the repo  
   ```bash
   git clone https://github.com/yourusername/california-crime-analysis.git
   cd california-crime-analysis
