# House Price Prediction - Linear Regression Model

This project predicts house prices based on features like area, number of bedrooms, parking, furnishing status, etc., using a Linear Regression model.

---

# What I Did Today

# 1. Dataset Loading & Inspection
- Loaded the dataset using `pandas`.
- Explored the data using `.head()`, `.info()`, `.describe()` to understand structure and detect missing values.

# 3. Data Preprocessing
- Applied one-hot encoding to convert categorical variables.
- Checked for and handled missing values using `.fillna(0)` or `.dropna()`.
  
# 4. Data Splitting
Split the dataset into training and testing sets using an 80-20 split:
- Split the data into independent features (`X`) and target (`y`).
# 5.Model Training and evaluation
-Trained the model using linear regression model and evaluated it.

# Results of evaluation
Mean Squared Error: 1313683610862.5579
R^2 Score: 0.6298518608872237
