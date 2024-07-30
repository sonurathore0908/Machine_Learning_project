Backorder Prediction Project

Overview
This project focuses on predicting backorders in e-commerce using machine learning techniques. By analyzing historical sales and inventory data, the goal is to forecast when items will be out of stock (backordered), helping businesses manage inventory more effectively and improve customer satisfaction.

Features
Data Collection & Integration: Connects to MongoDB and MySQL databases to gather and integrate structured and unstructured data.
Data Preprocessing: Cleans and prepares data for analysis, including feature engineering and normalization.
Model Building: Utilizes machine learning algorithms such as Logistic Regression and Random Forest to predict backorders.
Model Evaluation: Assesses model performance using metrics like accuracy, precision, recall, and F1 score.
Visualization: Provides visual insights into data distributions and model performance.
Deployment: Integrates the model into a Flask web application for real-time predictions.

Installation

To set up the project locally, follow these steps:
MongoDB: Ensure MongoDB is installed and running. Configure connection settings in config.py.
MySQL: Install MySQL and create a database. Update connection settings in config.py.

Prepare Data: Place your dataset files in the data directory.

Train the Model: Execute train_model.py to train the machine learning models with your data.
Predict Backorders: Use the Flask application to input new data and receive backorder predictions.

Libraries Used: Scikit-learn, Flask, Pandas, NumPy, Matplotlib.
