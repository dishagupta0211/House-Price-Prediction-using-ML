🏡 House Price Prediction using ML

This project predicts house prices using the California Housing dataset. It applies Machine Learning techniques (Linear Regression) to estimate housing prices based on features like MedInc, house age, average rooms,AveBedrms,AveOccup, population and MedHouseVal.


---

📂 Dataset

Dataset Name: California Housing

Source: Available in sklearn.datasets, Kaggle.

Features:

MedInc: Median income in block group

HouseAge: Median house age in block group

AveRooms: Average number of rooms

AveBedrms: Average number of bedrooms

Population: Block group population

AveOccup: Average house occupancy

Latitude & Longitude: Block group location




---

⚙ Tech Stack

Language: Python

Libraries:

NumPy

Pandas

Matplotlib / Seaborn




---

🚀 Steps in Project

1. Load and explore the dataset


2. Perform data preprocessing


3. Split dataset into training and testing sets


4. Train a Linear Regression model


5. Evaluate performance using metrics (RMSE, R² score)


6. Visualize predictions vs actual values




---

📊 Results

Model Performance:

R² Score: ~0.60 (approx., may vary depending on preprocessing & splits)

RMSE: ~0.70 (in 100,000 USD units → i.e., $70,000 average error)

MAE: ~0.50

The model explains around 60% of the variance in house prices.

Model performance can be improved by trying:

Feature scaling

Other algorithms (Random Forest, XGBoost)
