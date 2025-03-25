🚜 Bulldozer Price Prediction - Machine Learning Model

📌 Overview:
This project aims to build a **machine learning model** to predict the **sale price of bulldozers at auctions**. The dataset comes from **Kaggle's Blue Book for Bulldozers** competition and contains historical auction data, including machine usage, equipment type, configuration, and other factors that influence pricing.

🎯 Objective:
The goal is to predict future bulldozer prices based on past auction results using **data preprocessing, feature engineering, machine learning models, and hyperparameter tuning**.

🗂 Dataset:
The dataset consists of auction results from **Fast Iron**, a company specializing in data standardization for heavy equipment. The primary dataset used is `TrainAndValid.csv`.

📌 Key Features:

- `saledate` - Auction date
- `Usage` - Machine usage details
- `EquipmentType` - Type of equipment
- `SalePrice` - Price at auction (Target Variable)

🔗 [Kaggle Link](https://www.kaggle.com/c/bluebook-for-bulldozers)**

🛠 Machine Learning Pipeline

1. Data Preprocessing::

   - Parsing and handling `saledate`
   - Missing value imputation
   - Feature extraction (categorical encoding, datetime features)
   - Data cleaning and filtering

2. Exploratory Data Analysis (EDA):

   - Visualizing trends and correlations
   - Identifying outliers and data inconsistencies

3. Model Training & Evaluation:

   - **Baseline Model**: RandomForestRegressor
   - **Hyperparameter tuning**
   - **Performance metric**: Root Mean Squared Log Error (RMSLE)

4. **Predictions & Deployment**

   - Generating test predictions
   - Saving the trained model using `pickle/joblib`
   - Deploying via Flask API (optional)


## 📈 Model Performance

📌 **Best Model:** `RandomForestRegressor`
📌 **Evaluation Metric (RMSLE):** `0.xx` (to be updated after final tuning)

## 🤝 Contributing

Contributions are welcome! Feel free to submit pull requests or report issues.


🚜 **Predict Bulldozer Prices with Machine Learning!** 📊

