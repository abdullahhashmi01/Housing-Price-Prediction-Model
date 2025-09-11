# Housing-Price-Prediction-Model

### What I solved

I created a machine learning model to predict the price of houses using a housing dataset.

### Tools, methods, and frameworks used

I used the following tools, methods, and frameworks to solve the problem:
* **Libraries**:
    * `pandas` for data manipulation 
    * `numpy` for numerical operations 
    * `matplotlib.pyplot` for data visualization 
    * `sklearn` from the `scikit-learn` library for machine learning. The specific modules used were:
        * `train_test_split` to divide the data into training and testing sets 
        * `LinearRegression` to create the predictive model 
        * `mean_squared_error` and `r2_score` to evaluate the model's performance 
* **Methodology**:
    * ]**Data Preparation**: I loaded the `Housing.csv` dataset into a pandas DataFrame. I checked for missing values, but none were found. I then converted categorical features (like `mainroad`, `guestroom`, `furnishingstatus`, etc.) into a numerical format using one-hot encoding with `pd.get_dummies`.
    * **Model Training**: I split the data into a training set and a testing set with a 80/20 ratio. I then trained a `LinearRegression` model on the training data to predict the `price` based on the other features.
    * **Model Evaluation**: After training, I used the model to make predictions on the testing data. evaluated the model's performance using Mean Squared Error (MSE) and R-squared (R²). The model achieved a Mean Squared Error of 1023704618902.09 and an R-squared score of 0.70.

### Result and Impact

The developed `LinearRegression` model successfully predicts housing prices with a Mean Squared Error (MSE) of 1023704618902.09 and an R-squared (R²) score of 0.70. This R-squared value indicates that the model explains approximately 69.88 % of the variance in the housing prices. This is a good result for a simple model, demonstrating its ability to accurately predict prices based on key house characteristics. The scatter plot of actual versus predicted prices also shows that the predicted values are closely aligned with the actual prices.

Mean Squared Error: 1023704618902.09
R2 Score (Accuracy): 0.70
Model Accuracy: 69.88 %
