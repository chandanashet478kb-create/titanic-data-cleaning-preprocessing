# Titanic Dataset Cleaning and Preprocessing

## 📌 Project Overview
This project focuses on acquiring, exploring, cleaning, and preprocessing the Titanic passenger dataset using Python. The goal is to prepare the data for further analysis and machine learning.

## 📊 Dataset
The dataset contains information about 891 passengers and 12 columns, including passenger class, age, sex, fare, and survival status.

## 🛠️ Tools and Technologies
- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## 🔍 Tasks Performed
1. Loaded the Titanic dataset using Pandas.
2. Explored the dataset structure and statistical summary.
3. Identified missing values.
4. Filled missing Age values using the median.
5. Filled missing Embarked values using the mode.
6. Removed the Cabin column because it contained many missing values.
7. Checked for duplicate records.
8. Detected potential outliers in passenger fares using the IQR method.
9. Standardized categorical values.
10. Converted categorical variables into numerical columns using one-hot encoding.
11. Created a new FamilySize feature.
12. Scaled Age and Fare using MinMaxScaler.
13. Exported the cleaned and preprocessed datasets as CSV files.

## 📁 Project Files
- `train data ckeanin.ipynb` — Python notebook containing the code and outputs.
- `titanic_cleaned.csv` — cleaned dataset.
- `titanic_preprocessed.csv` — preprocessed dataset.

## ✅ Results
- Original dataset: 891 rows and 12 columns.
- Cleaned dataset: 891 rows and 11 columns.
- Preprocessed dataset: 891 rows and 15 columns.

## 📝 Conclusion
This project demonstrates the basic steps of data acquisition, exploration, cleaning, and preprocessing. The resulting datasets are ready for further analysis and can be used as a starting point for machine-learning experiments.
