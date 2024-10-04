# Customer Churn Prediction using ANN

This project focuses on predicting customer churn using an Artificial Neural Network (ANN). The goal is to help businesses identify customers who are likely to leave, allowing them to take preventive actions and improve customer retention.
# Features

    Data Preprocessing: Cleans and preprocesses customer data, including feature scaling, handling missing values, and encoding categorical variables.
    Artificial Neural Network (ANN): Implements a multi-layer ANN to predict customer churn based on historical data.
    Model Training and Evaluation: Trains the ANN model and evaluates it using accuracy, precision, recall, and other performance metrics.
    Visualizations: Provides visualizations of model performance and key factors affecting customer churn.
    Actionable Insights: Offers insights into customer behavior and suggestions for reducing churn.

# Requirements

    Python 3.8+
    Required libraries are listed in requirements.txt. Install them with:

    bash

    pip install -r requirements.txt

# Installation

    Clone the repository:

    bash

git clone https://github.com/Sreejeet1998/Customer_Churning_ANN.git

Navigate to the project directory:

bash

cd Customer_Churning_ANN

Install the required dependencies:

bash

    pip install -r requirements.txt

# Usage

    Prepare Dataset: Ensure you have the customer data in CSV format, which includes features like customer demographics, usage history, and churn labels.
    Train the Model: Train the ANN on your customer data to predict churn:

    bash

python train_ann_model.py --data customer_data.csv

Evaluate the Model: After training, evaluate the model on test data to measure performance:

bash

    python evaluate_model.py --test test_data.csv

    Generate Insights: Use the trained model to analyze customer behavior and gain insights into why customers churn.

# Customization

You can experiment with different ANN architectures, modify hyperparameters, or try different activation functions to improve prediction accuracy. The project is modular, allowing you to easily adjust the workflow.
# Contributing

Contributions are welcome! Feel free to fork the repository, enhance the code, and submit pull requests.
# License

This project is licensed under the MIT License. See the LICENSE file for more details.
