# Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Overview
This project performs Exploratory Data Analysis (EDA) on the Titanic dataset using **Python**, **Pandas**, **Matplotlib**, and **Seaborn**.  
The goal is to identify trends, patterns, and relationships in the data to understand the factors affecting passenger survival.

---

## 📂 Dataset
The analysis uses:
- `train.csv` — Training dataset containing passenger details and survival status.
- `test.csv` — Test dataset for predictions.
- `gender_submission.csv` — Example submission file for Kaggle competition.

Source: [Titanic Dataset on Kaggle](https://www.kaggle.com/c/titanic/data)

---

## 🛠 Tools Used
- **Python 3.x**
- **Pandas** — Data manipulation
- **Matplotlib** & **Seaborn** — Data visualization
- **Jupyter Notebook** — Interactive analysis

---

## 📊 Analysis Steps
1. **Data Loading & Inspection**
   - `.info()`, `.describe()`, `.value_counts()`
2. **Data Cleaning**
   - Handling missing values
   - Converting data types
3. **Visualization**
   - Histograms, Boxplots, Scatterplots
   - Correlation heatmap
   - Survival rate analysis by gender, class, age
4. **Observations**
   - Women had higher survival rates than men.
   - Passengers in higher classes had better chances of survival.
   - Younger passengers had a slightly better survival rate.

---

## 📈 Sample Plots
- Survival rate by gender
- Age distribution of survivors vs non-survivors
- Correlation heatmap of numeric features

---

## 📜 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/Titanic-EDA.git
