# -Predictive-Modeling-on-U.S.-Chronic-Disease-Indicators-
# 🩺 Exploratory Data Analysis & ML on U.S. Chronic Disease Indicators

This project explores the **U.S. Chronic Disease Indicators dataset** from [data.gov](https://data.gov) using Python. It includes a full workflow of **data cleaning**, **visualization**, **statistical testing**, and a **predictive machine learning model** built using **Linear Regression**.

---

## 📂 Dataset Source

- **Title**: U.S. Chronic Disease Indicators  
- **Publisher**: Centers for Disease Control and Prevention (CDC)  
- **Link**: [CDC Data Portal](https://data.cdc.gov/)  
- **Format**: CSV

---

## 🛠️ Technologies Used

- **Python 3.10+**
- **Libraries**:
  - `pandas`, `numpy` – data manipulation
  - `matplotlib`, `seaborn` – visualization
  - `scikit-learn` – machine learning
  - `scipy.stats` – statistical testing

---

## 🔍 Features & Workflow

### 1. Data Preprocessing
- Removed redundant columns and handled missing values
- Focused on key variables like `DataValue`, `Stratification`, `LocationDesc`, `Topic`

### 2. Exploratory Data Analysis (EDA)
- Histograms & box plots for numeric distributions
- Bar charts for top topics and locations
- Scatter plots to study relationships
- Pie & donut charts for category proportions
- Correlation heatmap

### 3. Statistical Testing
- **Z-Test**: Male vs Female health indicator values
- **T-Test**: California vs overall data values
- **F-Test**: Variance between Alcohol and Tobacco indicators

### 4. Machine Learning
- Built a **Linear Regression model** to predict `DataValue`
- One-hot encoded categorical variables
- Evaluated model performance with **RMSE** and **R² Score**
- Visualized **Actual vs Predicted** values

---

## 📈 Results

- Gained insights into the most prevalent health topics and regions
- Identified gender- and location-based differences in health indicators
- Built a baseline predictive model with reasonable accuracy

---

## 🚀 Future Scope

- Implement advanced ML models like Random Forest, XGBoost
- Time-series forecasting on indicator trends
- Geospatial visualizations using maps
- Deployment as an interactive web dashboard
- Integration with real-time or external datasets (weather, population, etc.)

---

## 📚 References

- [U.S. Chronic Disease Indicators Dataset – data.cdc.gov](https://data.cdc.gov/)
- Python, Pandas, NumPy, Seaborn, Matplotlib, scikit-learn, Jupyter
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [Project Jupyter](https://jupyter.org/)

---

## 📌 Author

**Gottam Dhanush**  
Data Science & Analytics Enthusiast  
[LinkedIn](https://www.linkedin.com) *(add your profile link)*

---

## 📌 License

This project is open-source and free to use for educational and non-commercial purposes.
