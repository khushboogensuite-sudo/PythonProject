# 💤 Sleep Quality Analysis Using Python

## 📌 Project Overview

This project analyzes the factors that influence **Sleep Quality** using Python. The analysis includes data cleaning, exploratory data analysis (EDA), statistical hypothesis testing, linear regression modeling, and data visualization.

The objective is to identify relationships between variables such as **Age**, **Gender**, **Physical Activity Level**, **Sleep Duration**, **Bedtime**, **Wake-up Time**, and **Sleep Disorders** with **Sleep Quality**.

---

# 📊 Dataset

**Dataset:** Health Sleep Statistics

The dataset contains information about individuals' sleeping habits, demographics, physical activity levels, and sleep quality.

### Features Used

* Age
* Gender
* Physical Activity Level
* Bedtime
* Wake-up Time
* Sleep Quality
* Sleep Disorders

---

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* SciPy
* Kaggle Notebook

---

# 📂 Project Workflow

## 1. Data Loading

* Imported dataset from Kaggle
* Created a Pandas DataFrame

```python
df = pd.read_csv(...)
```

---

## 2. Data Exploration

Performed:

* Dataset size
* Column names
* Data types
* Summary statistics
* Missing value analysis
* Duplicate value analysis

Functions used:

* `head()`
* `info()`
* `describe()`
* `isna()`
* `duplicated()`

---

## 3. Data Cleaning

Performed the following preprocessing steps:

* Removed unnecessary **User ID** column
* Converted **Bedtime** and **Wake-up Time** into numerical values
* Created a new feature:

  * Sleep Duration
* Converted Physical Activity Level into numerical values

Mapping:

| Category | Value |
| -------- | ----: |
| Low      |     1 |
| Medium   |     2 |
| High     |     3 |

---

# 📈 Exploratory Data Analysis (EDA)

The following analyses were performed.

## Age vs Sleep Quality

* Correlation analysis
* Linear Regression
* Scatter Plot
* Regression Line

Observation:

* Sleep quality decreases as age increases.

---

## Gender vs Sleep Quality

Visualization:

* Bar Plot

Performed:

* Independent Sample t-test

Generated:

* t-statistic
* p-value

---

## Physical Activity vs Sleep Quality

Visualization:

* Bar Plot

Analysis:

* Average sleep quality across different activity levels.

---

## Gender vs Physical Activity

Visualization:

* Bar Plot

Statistical Test:

* Independent Sample t-test

Generated:

* t-statistic
* p-value

---

## Bedtime vs Sleep Quality

Visualization:

* Bar Plot

---

## Wake-up Time vs Sleep Quality

Visualization:

* Bar Plot

---

## Sleep Duration vs Sleep Quality

Performed:

* Linear Regression
* Scatter Plot
* Regression Line

Generated:

* Coefficient
* Intercept
* Predictions

---

## Sleep Disorders vs Sleep Quality

Visualization:

* Box Plot

Used to compare the distribution of sleep quality across different sleep disorder categories.

---

## Correlation Analysis

Generated a correlation heatmap for all numerical variables.

Visualization:

* Heatmap

---

# 📊 Machine Learning

## Linear Regression Models

### Model 1

Predictor:

* Age

Target:

* Sleep Quality

Outputs:

* Regression Line
* Coefficient
* Intercept
* Predictions

---

### Model 2

Predictor:

* Sleep Duration

Target:

* Sleep Quality

Outputs:

* Regression Line
* Coefficient
* Intercept
* Predictions

---

# 📐 Statistical Analysis

Performed Independent Sample t-tests using SciPy.

Used:

```python
stats.ttest_ind()
```

Calculated:

* t-statistic
* p-value

Purpose:

To determine whether differences between male and female groups were statistically significant.

---

# 📉 Visualizations

The project includes:

* Bar Charts
* Scatter Plots
* Regression Line Plots
* Box Plots
* Correlation Heatmap

Libraries Used:

* Matplotlib
* Seaborn

---

# 📌 Key Findings

* Age shows a negative relationship with Sleep Quality.
* Sleep Duration positively impacts Sleep Quality.
* Physical Activity Level influences Sleep Quality.
* Sleep Disorders significantly affect Sleep Quality.
* Correlation analysis helped identify relationships among numerical features.
* Linear Regression models were used to predict Sleep Quality.
* Statistical hypothesis testing was performed using t-tests.

---

# 📁 Project Structure

```
Sleep-Quality-Analysis/
│
├── README.md
├── Sleep_Quality_Analysis.ipynb
├── Health_Sleep_Statistics.csv
└── images/
```

---

# 🚀 Future Improvements

* Multiple Linear Regression
* Random Forest Regression
* Feature Engineering
* Model Evaluation using:

  * R² Score
  * MAE
  * RMSE
* Hyperparameter Tuning
* Interactive Dashboard using Power BI

---

# 📚 Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis
* Feature Engineering
* Statistical Analysis
* Hypothesis Testing
* Correlation Analysis
* Linear Regression
* Data Visualization
* Python Programming

---

# 👩‍💻 Author

**Khushboo Singh**

Business Analyst | Aspiring Data Analyst

---

# ⭐ If you found this project useful, consider giving it a star on GitHub!
