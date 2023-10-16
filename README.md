# House-Prices--Advanced-Regression-Techniques
**Data:** The dataset contains 80 input features, and 1 Target variable called SalePrice. We're expected to predict the sale price of different houses with various features such as MSSubClass, LotFrontage, LotArea, etc. This is a Regression problem. You can import dataset from the [following link](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data) to replicate the same results and follow along the experiement. We'll use XgBoost to solve this problem.

**Important learnings: **
* Wite a re-usable function to determine data type, Null Counts,	Unique values, and Null_Percent in each variable and store in a dataframe.
* Feature Engineering.
* Easy method to check Null values across different features in dataset.
* Encode rare categories using RareLabelEncoder.
* Creating Class for temporal transformation that is compatible with SK_learn pipeline.
* Building the Pre-Processing sklearn pipeline for data preprocessing such missing value imputation, feature engineering, data encoding, etc.
* Calculate the feature importance
* Automatic important feature selection using SelectFromModel.
* Compare different model version such as Model without preprocessing data, Model with processed data, and Model with important variables only.
