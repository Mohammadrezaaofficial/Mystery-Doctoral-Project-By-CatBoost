# Mystery-Doctoral-Project-By-CatBoost

## Summary
The document introduces CatBoost, a machine learning algorithm, highlighting its advantages over similar tools like XGBoost. The key benefits mentioned are its ability to automatically tune parameters and its use of a GPU for faster data processing. The document then proceeds to the initial steps of a data science project: loading and inspecting a dataset called train.csv which contains both categorical (cat) and continuous (cont) features. The target variable in this dataset is "loss".


## 1. Introduction to CatBoost: 
The document starts by explaining that CatBoost is a more advanced version of XGBoost. It has the capability to perform its own parameter tuning automatically. A significant advantage noted is that CatBoost can utilize a GPU to process data, which is faster than using a CPU. The document also provides the pip command to install the library.


## 2. Data Loading and Initial Inspection:
The project then loads a CSV file named train.csv into a pandas DataFrame. The document displays the first few rows of the data, which contains 132 columns and 188,318 rows. It categorizes the columns into two types:

cat columns: These are categorical features, represented by letters like 'A' and 'B'.

cont columns: These are continuous features, containing numerical values that have been min-max scaled.


The target variable, which is the value to be predicted, is the loss column.

## 3. Data Quality Check: 
The document checks for missing values in the dataset using df.isnull().sum() and df.isnull().sum().sum(). The results show that there are no missing values across all columns. A statistical summary of the continuous columns is also shown, providing details like the count, mean, standard deviation, and quartiles.

## Conclusion
The document serves as an initial introduction to using the CatBoost library, covering the fundamental steps of data loading, initial inspection, and data quality checks. However, the provided content does not include any further steps in the machine learning process, such as training the CatBoost model, making predictions, or evaluating its performance with metrics like a classification report or confusion matrix. As such, a conclusion on the model's effectiveness in predicting the loss cannot be drawn from the information in this document alone.
