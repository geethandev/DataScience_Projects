# Automobile MPG Prediction with Data Science and GUI
![Project Image](project_img.jpg) 
## Project Overview
This project aims to build a predictive model to estimate the miles per gallon (MPG) of automobiles based on various features such as cylinders, displacement, horsepower, weight, and acceleration. The project involves the following key steps:

1. Data Collection and ETL using SSIS: The dataset is collected, and the Extract, Transform, Load (ETL) process is performed using SQL Server Integration Services (SSIS) to prepare the data for data science analysis.

2. Exploratory Data Analysis (EDA): We explore the dataset using Python's pandas and matplotlib libraries to gain insights into the data and visualize the relationships between different features.

3. Linear Regression Model: We build a Linear Regression model using scikit-learn to predict the MPG based on the given features.

4. Graphical User Interface (GUI): A Tkinter-based GUI application is created to allow users to input values for the features and get predictions for the MPG using the trained Linear Regression model.

## Getting Started
To run the project, follow these steps:

1. Data Collection: Ensure you have the dataset in a CSV file named "automobile.csv." - you can found the dataset in the data Folder

2. ETL using SSIS: Use SQL Server Integration Services to perform the ETL process on the dataset and save the cleaned data in a database table.

3. Data Science Part:
   - Install the required Python libraries (pandas, scikit-learn, matplotlib, etc.).
   - Run the Jupyter Notebook or Python script for Exploratory Data Analysis (EDA) to understand the dataset.
   - Train the Linear Regression model on the cleaned data.

4. GUI Part:
   - Install the necessary Python library: Tkinter (it is usually included with Python).
   - Load your trained Linear Regression model using `joblib` or `pickle`.
   - Run the Python script for the Tkinter-based GUI application.

## Requirements
- Python 3.9
- Libraries: pandas, scikit-learn, matplotlib, tkinter (included with Python)
- SQL Server (for ETL process)

## Author
- Geethandev

