# Customer Churn Prediction Model

This project involves building a machine learning model to predict customer churn for a subscription-based business. By analyzing customer behavior data, transaction history, and support interaction logs, the model identifies at-risk customers and suggests retention strategies.

## Tech Stack
- **Python**: Logistic Regression, Decision Trees, XGBoost
- **Azure Databricks**: For model training and deployment
- **SQL Server**: Data storage and queries
- **Power BI**: Churn analysis and real-time prediction dashboard

## Key Features
- **Data Wrangling**: Cleaning and preparing data for model training
- **Feature Extraction**: Identifying relevant features for churn prediction
- **Model Evaluation**: Using confusion matrix and AUC-ROC to evaluate model performance
- **Real-Time Prediction Dashboard**: Visualizing churn predictions and strategies for retention

## Getting Started

These instructions will help you set up and run the project locally.

### Prerequisites

Make sure you have the following installed:
- Python >= 3.8
- Azure Databricks environment
- SQL Server (or access to a database)
- Power BI for visualization

### Installation

1. Clone the repository:
   git clone https://github.com/ssanjaychandra123/Customer-Churn-Prediction-Model.git
   
3. Install dependencies:
   pip install -r requirements.txt

4. Set up Azure Databricks:
   Upload the dataset to Azure Databricks.
   Configure the environment for model training within Databricks.

5. Run the model:
   Execute the Python scripts to preprocess the data, train the model, and generate predictions.

6. Power BI integration:
   Connect Power BI to the Azure Databricks model for real-time predictions.

### Results
The model successfully identifies at-risk customers, achieving a high AUC-ROC score and providing actionable insights through a real-time dashboard.

### Contributing
If you'd like to contribute, please follow these steps:

Fork the repository.
Create a new branch.
Make your changes.
Open a pull request.
