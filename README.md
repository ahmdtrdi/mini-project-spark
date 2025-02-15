# mini-project-spark
This project leverages machine learning to predict house prices using the square footage of living space (sqft_living) as our primary feature. We'll follow the CRISP-DM (Cross-Industry Standard Process for Data Mining) workflow to ensure a structured and effective approach.

Link Drive : https://drive.google.com/drive/folders/1OwJlN4NfQnr-CUcXfqIh2gpcFgZ9Y1FH?usp=sharing

# Business Understanding
Goal: Develop an accurate prediction model for house prices based on living space area.

# Data Understanding
We'll be working with housing data containing:

- Target Variable: House prices
- Primary Feature: Square footage of living space (sqft_living)

# Data Preparation
Our preparation steps include:

- Loading data
- Cleaning any missing values
- Feature scaling if necessary
- Splitting data into training and testing sets

# Modeling

implement Linear Regression using Linear Regression

model = LinearRegression()

model.fit(X_train, y_train)

y_pred = model.predict(X_test)

# Evaluation

| Metric | Value |
|--------|-------|
| Mean Squared Error (MSE) | 0.1254 |
| Root Mean Squared Error (RMSE) | 0.3541 |

![lr](https://github.com/user-attachments/assets/d07e214c-cdb2-4259-a914-97ea5b8909e9)

