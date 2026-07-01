# Property Price Prediction

This project is my first attempt at applying the machine learning concepts i've learned so far including data preprocessing feature engineering linear regression and model evaluation.

## Dataset

The project uses the California Housing dataset to predict median house prices based on various housing features such as:

- Longitude
- Latitude
- Housing Median Age
- Total Rooms
- Total Bedrooms
- Population
- Households
- Median Income
- Ocean Proximity

---

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- joblib

---

## Project Workflow

- Loaded and explored the dataset
- Checked for missing values
- Filled missing values using the median
- One-Hot Encoded categorical features
- Split the dataset into training and testing sets
- Standardized numerical features using StandardScaler
- Trained a Linear Regression model
- Predicted house prices on unseen data
- Evaluated the model using regression metrics
- Visualized model performance
- Saved the trained model using Joblib

---

## Model Evaluation

| Metric | Score |
|--------|--------|
| MAE | 48813.14 |
| MSE | 4423298726.09 |
| RMSE | 66507.88 |
| R² Score | 0.6583 |

---

## Visualizations

The notebook includes:

- Actual vs Predicted House Prices
- Residual Plot
- Distribution of Prediction Errors

---

## Technologies Used

- Python
- Jupyter Notebook
- Scikit-Learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Future Improvements

As I continue learning Machine Learning, I plan to improve this project by experimenting with:

- Multiple Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting
- Hyperparameter Tuning
- Cross Validation

---

## What I Learned

Through this project, I gained hands-on experience with:

- Data preprocessing
- Handling missing values
- One-Hot Encoding
- Feature Scaling
- Train-Test Splitting
- Linear Regression
- Model Evaluation using MAE, MSE, RMSE, and R²
- Visualizing model performance
