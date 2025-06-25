# 🌍 Life Expectancy Predictor

This project builds a regression model to estimate **life expectancy** across countries using a range of **socioeconomic and health-related factors**, including:

- Gross Domestic Product (GDP)
- Education level
- Healthcare expenditure
- Immunization rates
- and other development indicators

---

## 📂 Dataset Source

This dataset was originally published on [Kaggle](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who) by **KumarRajarshi**. It contains global life expectancy data curated from WHO and other development indicators.

---

## 📖 Dataset Description

This project aims to predict the life expectancy of a given country based on various health, economic, and demographic parameters. The dataset includes the following variables:

- **Country**: Name of the country  
- **Year**: Year of the data record  
- **Status**: Development status (Developed or Developing)  
- **Life Expectancy**: Average expected lifespan in years  
- **Adult Mortality**: Number of adult deaths per 1000 population  
- **Infant Deaths**: Number of infant deaths per 1000 live births  
- **Alcohol**: Alcohol consumption per capita (in liters)  
- **Percentage Expenditure**: Health expenditure as a percentage of GDP  
- **Hepatitis B**: Immunization coverage percentage for Hepatitis B  
- **Measles**: Number of reported measles cases  
- **BMI**: Average Body Mass Index of the population  
- **Under Five Deaths**: Number of deaths of children under five years  
- **Polio**: Immunization coverage percentage for Polio  
- **Total Expenditure**: Total health expenditure per capita  
- **Diphtheria**: Immunization coverage percentage for Diphtheria  
- **HIV/AIDS**: Death rate per 1000 due to HIV/AIDS  
- **GDP**: Gross Domestic Product per capita  
- **Population**: Total population of the country  
- **Thinness 1-19 years**: Prevalence of thinness among children and adolescents aged 1–19  
- **Thinness 5-9 years**: Prevalence of thinness among children aged 5–9  
- **Income Composition of Resources**: Indicator of income inequality and distribution  
- **Schooling**: Average years of schooling in the population  

This dataset provides a broad view of factors influencing life expectancy, enabling the development of predictive models to analyze health outcomes globally.

---

## 📊 Project Highlights

- ✅ **Data Cleaning & Preprocessing**: Handled missing values, encoded categorical features, and normalized continuous variables.
- 📈 **Correlation Analysis & Feature Selection**: Used heatmaps and feature importance (via Random Forest) to select relevant predictors.
- 🧠 **Modeling & Evaluation**:
  - Algorithms tested: Linear Regression, SVR, RandomForest, and ensemble models.
  - Hyperparameter tuning via GridSearchCV.
  - Final model: **VotingRegressor** combining RandomForest and LinearRegression.
  - Best RMSE: **1.66 years**

---

## 🔧 Tools & Libraries

- `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`
- `scikit-learn`
- Jupyter Notebook

---
