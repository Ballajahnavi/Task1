# Task1
# Titanic Data Preprocessing

## Steps:
1. **Loaded** the dataset and explored basic info.
2. **Handled missing values** (`Age`, `Embarked`) and dropped `Cabin`.
3. **Encoded categorical features** (`Sex`, `Embarked`) using one-hot encoding.
4. **Standardized** numerical features (`Age`, `Fare`) using `StandardScaler`.
5. **Removed outliers** using the IQR method.

The cleaned dataset is ready for model training.

## Requirements:
- pandas
- scikit-learn
- seaborn
- matplotlib
