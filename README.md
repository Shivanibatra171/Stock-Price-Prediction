# 📈Stock-Price-Prediction
A machine learning project that predicts stock closing prices using historical market data.
🔍 Problem Statement
Given historical stock data (Open, High, Low, Close, Volume), predict the next day's closing price.
🛠️ Technologies Used

Python
Pandas, NumPy
Scikit-learn (Linear Regression)
MinMaxScaler (data normalization)

📊 Dataset

Historical stock price dataset with features: Open, High, Low, Close, Volume
80/20 train-test split

⚙️ Approach

Data loading and cleaning (handled missing values with forward fill)
Feature selection: Open, High, Low, Volume → predict Close
Data normalization using MinMaxScaler

📁 Files
FileDescriptionStock_Price_Prediction.ipynbMain Jupyter notebook
StockPriceDataset.csvHistorical stock data

👩‍💻 Author
Shivani Batra — CS Student at Sukkur IBA University (AI Specialization)
LinkedIn | GitHub
Model training with Linear Regression
Evaluation using MSE and R² Score
