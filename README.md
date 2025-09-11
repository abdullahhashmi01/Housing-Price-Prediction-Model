# Housing-Price-Prediction-Model

### What I solved

I created a machine learning model to predict the price of houses using a housing dataset.

### Tools, methods, and frameworks used

[cite_start]I used the following tools, methods, and frameworks to solve the problem[cite: 1]:
* **Libraries**:
    * [cite_start]`pandas` for data manipulation [cite: 1]
    * [cite_start]`numpy` for numerical operations [cite: 1]
    * [cite_start]`matplotlib.pyplot` for data visualization [cite: 1]
    * [cite_start]`sklearn` from the `scikit-learn` library for machine learning[cite: 1]. The specific modules used were:
        * [cite_start]`train_test_split` to divide the data into training and testing sets [cite: 1]
        * [cite_start]`LinearRegression` to create the predictive model [cite: 1]
        * [cite_start]`mean_squared_error` and `r2_score` to evaluate the model's performance [cite: 1]
* **Methodology**:
    * [cite_start]**Data Preparation**: I loaded the `Housing.csv` dataset into a pandas DataFrame[cite: 1]. [cite_start]I checked for missing values, but none were found[cite: 1]. [cite_start]I then converted categorical features (like `mainroad`, `guestroom`, `furnishingstatus`, etc.) into a numerical format using one-hot encoding with `pd.get_dummies`[cite: 1].
    * [cite_start]**Model Training**: I split the data into a training set and a testing set with a 80/20 ratio[cite: 1]. [cite_start]I then trained a `LinearRegression` model on the training data to predict the `price` based on the other features[cite: 1].
    * [cite_start]**Model Evaluation**: After training, I used the model to make predictions on the testing data[cite: 1]. [cite_start]I evaluated the model's performance using Mean Squared Error (MSE) and R-squared (R²)[cite: 1]. [cite_start]The model achieved a Mean Squared Error of 1023704618902.09 and an R-squared score of 0.70[cite: 1].

### Result and Impact

[cite_start]The developed `LinearRegression` model successfully predicts housing prices with a Mean Squared Error (MSE) of 1023704618902.09 and an R-squared (R²) score of0.70[cite: 1]. [cite_start]This R-squared value indicates that the model explains approximately 69.88 % of the variance in the housing prices[cite: 1]. This is a good result for a simple model, demonstrating its ability to accurately predict prices based on key house characteristics. [cite_start]The scatter plot of actual versus predicted prices also shows that the predicted values are closely aligned with the actual prices[cite: 1].

Mean Squared Error: 1023704618902.09
R2 Score (Accuracy): 0.70
Model Accuracy: 69.88 %
