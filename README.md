## House Price Prediction
A machine learning project to predict housing prices using a Linear Regression model.

# 1. Project Overview
This project aims to predict the median value of homes in Boston neighborhoods based on various features. It serves as an end-to-end regression analysis, covering data preprocessing, model training, and performance evaluation. The primary goal is to build a simple yet effective model to predict a continuous value (price) rather than a category.

# 2. Dataset
The project uses a well-known housing dataset. It contains 13 features and a target variable for the median house price. A key characteristic of this dataset is that it has no header, so columns are referenced by their index. The data was cleaned to handle missing values by filling them with the column mean.

**Target Variable:**

Index 13: Median value of owner-occupied homes in dollars.

# 3. Methodology
The project follows a standard machine learning workflow for regression tasks:

Data Loading and Cleaning: The data is loaded, and missing values are handled using a robust imputation method.

Data Splitting: The dataset is split into training and testing sets to ensure the model's performance is evaluated on unseen data.

Model Training: A Linear Regression model is trained on the training data.

Model Evaluation: The model's performance is measured using standard regression metrics.

# 4. Results
The trained Linear Regression model provides a solid baseline for house price prediction. The final performance on the test set is as follows:

RMSE: [3.744]

Interpretation: This is the average difference between our predicted price and the actual price, in thousands of dollars. For example, an RMSE of 3.744 means our predictions are, on average, off by about $3,744.

R² Score: [0.799]

Interpretation: This score, from 0 to 1, indicates how well our model's predictions fit the actual data. An R² of 0.799 means the model explains about 80% of the variance in house prices.

# 5. Technologies Used -
   
Python
Pandas, NumPy
Matplotlib (for visualization)
Scikit-learn (LinearRegression, train_test_split, metrics)

# 6. How to Run the Project -

To run this project, you need to have Python and the required libraries installed.

**Clone the repository:**

```bash
git clone https://github.com/[your-username]/House-Price-Prediction.git
```

**Navigate to the project directory:**

```bash
cd House-Price-Prediction
```
