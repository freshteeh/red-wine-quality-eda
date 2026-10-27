# Exploratory Data Analysis (EDA) on Red Wine Quality Dataset

This project contains a comprehensive Exploratory Data Analysis (EDA) performed on the classic **Red Wine Quality** dataset using Python and Pandas.

## 📊 Dataset Information
The dataset is related to the red variants of the Portuguese "Vinho Verde" wine. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (output) variables are available.
- **Input Variables:** Fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol.
- **Output Variable:** Quality (score between 0 and 10).

## 🛠️ Libraries Used
- `pandas` - Data manipulation and cleaning
- `numpy` - Numerical operations
- `matplotlib` & `seaborn` - Data visualization (Correlation matrix, distributions, etc.)

## 🚀 Key Steps Performed
1. **Data Loading & Inspection:** Loaded the dataset using Pandas, checked data types, and inspected sample rows.
2. **Data Cleaning:** Handled missing values and identified/removed duplicate records (reduced from 1599 to 1359 rows).
3. **Statistical Summary:** Generated descriptive statistics (mean, std, min, max, percentiles) for all features.
4. **Correlation Analysis:** Explored the relationships between different physicochemical properties and wine quality (notably observing the strong positive correlation of alcohol with quality).

## 📂 Project Structure
