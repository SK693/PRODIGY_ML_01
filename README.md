# PRODIGY_ML_01
## House Price Prediction using Linear Regression
### Task Overview
This task involves predicting the prices of houses based on their square footage, number of bedrooms, and number of bathrooms using a Linear Regression model. The project includes data loading, preprocessing, model training, evaluation, and visualization to achieve accurate price predictions.

### Dependencies
The task requires the following libraries:

os
pandas
numpy
scikit-learn
plotly
matplotlib

### How the Code Works?
#### 1. Load and Preprocess Data
A function is defined to load data from CSV files using Pandas. The relevant features (beds, baths, size) and the target variable (price) are extracted and normalized for better model performance.

##### 2. Load Dataset
Training and testing data are loaded from their respective CSV files. The data is split into features and target variables for both training and testing datasets.

#### 3. Train Linear Regression Model
A Linear Regression model is trained using the training data. The model learns the relationship between the features and the house prices during this training phase.

#### 4. Evaluate the Model
The trained model is evaluated on the test set. Mean Squared Error (MSE) and Root Mean Squared Error (RMSE) are calculated to assess the model's performance. Additionally, various visualizations are created to analyze the model's predictions and the relationships between different features.

#### 5. Visualizations
Several visualizations are created to understand the model's performance and the data:

##### Actual vs Predicted Prices Scatter Plot: Shows the relationship between actual and predicted house prices.
##### Heatmap of Residuals: Displays the residuals (errors) of the predictions.
##### Correlation Matrix Heatmap: Illustrates the correlation between different features and the target variable.
##### Scatter Matrix of Features and Target: Provides a comprehensive visualization of the features and the target variable.

#### 6. Conclusion
This task demonstrates the application of linear regression to predict house prices using basic features such as the number of bedrooms, bathrooms, and square footage. The visualizations help in understanding the model's performance and the relationships between different features.
