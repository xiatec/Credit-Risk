# Credit-Default-Analysis-Using-Databricks-Pyspark-ML-Model
**Project Name: Credit Card Default Prediction**

**Description:**

In this project, we have developed machine learning models using big data technologies such as PySpark to predict whether a customer will default on their next credit card payment. The dataset used in this project is sourced from the UCI Machine Learning Repository.

**Dataset Attributes:**

This research employed a binary variable, default payment (Yes = 1, No = 0), as the response variable. The dataset includes the following 23 explanatory variables:

1. **X1:** Amount of the given credit (NT dollar).
2. **X2:** Gender (1 = male; 2 = female).
3. **X3:** Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).
4. **X4:** Marital status (1 = married; 2 = single; 3 = others).
5. **X5:** Age (year).
6. **X6 - X11:** History of past payment. Repayment status from April to September 2005.
7. **X12 - X17:** Amount of bill statement (NT dollar) from April to September 2005.
8. **X18 - X23:** Amount of previous payment (NT dollar) from April to September 2005.

**Technologies Used:**

- PySpark
- Databricks
- Spark SQL
- Machine Learning models (MLlib)

**How to Use:**

1. **Data Preparation:**
   - Download the dataset from the UCI Machine Learning Repository.
   - Ensure that the dataset is formatted correctly and contains all necessary attributes.

2. **Setting up Environment:**
   - Create a databricks community edition account which is free to use with some restrictions.
   - Set up a Databricks cluster for running PySpark code.

3. **Running the Project:**
   - Use PySpark to load the dataset into a Spark DataFrame.
   - Perform data preprocessing and feature engineering using Spark SQL and PySpark functions.
   - Train machine learning models using MLlib provided by PySpark.
   - Evaluate model performance and tune hyperparameters as necessary.



**Acknowledgments:**
- UCI Machine Learning Repository for providing the dataset.
- Databricks community edition platform.
