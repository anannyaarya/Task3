# Task 3: Linear Regression - House Price Prediction

## Objective
To implement and understand both **Simple** and **Multiple Linear Regression** using a real-world housing dataset. The goal is to predict house prices based on numerical and categorical features.


## Tools & Libraries
- Python
- Pandas
- scikit-learn
- Matplotlib
- Seaborn


## Dataset Overview
The dataset contains 545 rows with the following features:

- `area`, `bedrooms`, `bathrooms`, `stories`, `parking` (Numerical)
- `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `prefarea` (Binary categorical: yes/no)
- `furnishingstatus` (Categorical: furnished, semi-furnished, unfurnished)
- `price` (Target variable)


## Tasks Completed

### Data Preprocessing
- Converted categorical columns using label encoding and one-hot encoding.
- Checked for null values and data types.

### Simple Linear Regression
- Feature: `area`
- Target: `price`
- Plotted regression line

### Multiple Linear Regression
- Features: All relevant numerical + encoded categorical features
- Target: `price`

### Model Evaluation
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R² Score (R-squared)**

---

## Results

| Model Type              | MAE                   | MSE                        | R² Score                    |
|-------------------------|-----------------------|----------------------------|-----------------------------|
| Simple Linear Regression| *1474748.1337969352*  | *3675286604768.185*        | *0.27287851871974644*       |
| Multiple Linear Regression| *970043.4039201637* | *1754318687330.6633*       | *0.6529242642153185*        |




## Files Included

- `Task3.ipynb` - Jupyter notebook with full implementation
- `Housing.csv` - Dataset used for training
- `README.md`
- `plot.png` 


## Learnings

- How to apply Linear Regression to real-world data
- Difference between simple and multiple regression
- How to preprocess categorical variables
- Evaluating regression models using proper metrics
- Visualizing and interpreting model outputs


