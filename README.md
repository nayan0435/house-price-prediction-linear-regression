# house-price-prediction-linear-regression
End-to-end Machine Learning project for predicting house prices using Linear Regression, including EDA, feature engineering, scaling, and model evaluation.
#  House Price Prediction using Linear Regression

##  Project Overview
This project predicts house prices using multiple features such as area, bedrooms, bathrooms, and grade.  
The complete Machine Learning pipeline is implemented including EDA, feature scaling, train-test split, and model evaluation.



##  Problem Statement
To build a regression model that can predict house prices based on property features.



##  Dataset
The dataset contains the following features:

- sqft_lot → Total lot area
- sqft_living → Living area
- bedrooms → Number of bedrooms
- bathrooms → Number of bathrooms
- grade → Construction quality
- price → Target variable



##  Exploratory Data Analysis (EDA)

The following visualizations were performed:

- Price Distribution
- Area vs Price Scatter Plot
- Correlation Heatmap

### Key Observations:
- Lot area had very weak correlation (~0.05) with price.
- Living area and grade showed stronger positive correlation.
- Multiple features were required for better prediction.



##  Feature Engineering

- Missing values handled
- One-hot encoding applied for categorical variables (if present)
- Feature scaling performed using StandardScaler



##  Train-Test Split

The dataset was divided into:

- 80% Training Data
- 20% Testing Data



## Model Used

Linear Regression was chosen because:

- Positive linear trends were observed during EDA
- Model is interpretable
- Suitable for continuous target variable



## Model Evaluation

Metrics used:

- Mean Squared Error (MSE)
- R² Score

The model achieved a reasonable R² score indicating good predictive performance.



##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn



##  How to Run the Project

1. Clone the repository
2. Install requirements:
   pip install -r requirements.txt
3. Run the Jupyter Notebook



##  Conclusion

Although lot area showed weak linear relationship with price,
combining multiple features improved model performance significantly.

This project demonstrates a complete end-to-end ML workflow.
