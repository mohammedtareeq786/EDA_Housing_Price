# EDA_Housing_Price
This document talks about:

EDA_Housing_Price: A Jupyter notebook that explores the data and builds a model for predicting house prices using Python libraries and Gradient Boosting Regressor.

Data loading and exploration: The notebook loads the train and test data from CSV files and examines the shape, columns, null values, descriptive statistics, and outliers of the data.

Feature engineering: The notebook selects some important features based on domain knowledge and data analysis, and deals with outliers by dropping rows with extreme values.

Preprocessing: The notebook applies SimpleImputer for numerical data and Pipeline for categorical data, and bundles them into a ColumnTransformer for both train and test data.

Modelling: The notebook uses GradientBoostingRegressor with some hyperparameters to fit the train data and predict the test data, and creates a submission DataFrame with Id and SalePrice columns.
