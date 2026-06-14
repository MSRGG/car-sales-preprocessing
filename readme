# Car Sales Data Preprocessing Pipeline

This repository contains a Jupyter Notebook demonstrating an end-to-end data preprocessing pipeline using **scikit-learn** and **pandas**. The pipeline effectively handles missing values (imputation) and converts categorical text features into numerical values (one-hot encoding) to prepare the data for machine learning algorithms.

## 🚀 Features Covered
* **Target Isolation:** Dropping rows with missing labels (`Price`) to maintain training integrity.
* **Feature Imputation:** * Categorical features (`Make`, `Colour`) filled with a constant value (`"missing"`).
  * Feature variables like `Doors` handled with a specific baseline default (`4`).
  * Continuous numerical data (`Odometer (KM)`) handled via `mean` strategy imputation.
* **Categorical Encoding:** Utilizing `OneHotEncoder` inside a `ColumnTransformer` to seamlessly binarize categorical features while safely bypassing remaining untouched columns via `passthrough`.
* **Data Integration:** Converting dense processed matrices back into clearly labeled Pandas DataFrames using auto-generated transformer feature names.

## 🛠️ Tech Stack & Libraries
* **Python 3.14+**
* **Pandas** (Data manipulation and cleaning)
* **NumPy** (Array manipulations)
* **Scikit-Learn** (Data preprocessing & transformation pipelines)
