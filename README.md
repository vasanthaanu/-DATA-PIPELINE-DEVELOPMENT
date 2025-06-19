# -DATA-PIPELINE-DEVELOPMENT
COMPANY: CODTECH IT SOLUTIONS

NAME: VASANTHA AVULURI

INTERN ID:CT04DF992

DOMAIN: DATA SCIENCE

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

#DESCRIPTION:

ETL Data Pipeline Project with Python, Pandas & Scikit-learn

This project demonstrates the implementation of an automated ETL (Extract, Transform, Load) data pipeline using Python. The core functionality is contained in the script file named datapipeline.py, while the output of the processed data is saved in data.csv. The project showcases how to handle real-world tabular data using widely adopted data science tools like pandas and scikit-learn, and it is designed to be both educational and extendable for production-grade applications.

All development and execution were performed in Visual Studio Code (VS Code) on a Windows environment.

📁 Project Files

datapipeline.py – The main Python script that implements the ETL logic.

data.csv – A CSV file containing the output data.

🧱 Project Overview

The datapipeline.py script is built to simulate a full end-to-end ETL pipeline. It begins by checking whether a CSV file exists in the target folder. If not, it generates a synthetic dataset containing sample data about individuals (e.g., Name, Age, Gender, Salary). After ensuring the presence of the dataset, the script extracts the data, applies preprocessing transformations, and then loads the cleaned and transformed data into a new CSV file (data.csv).

The project adheres to industry-standard practices for data preparation, ensuring the data is structured and normalized for downstream machine learning or analytics workflows.

🧰 Tools & Libraries Used

Python – Core programming language used for scripting.

pandas – Utilized for data ingestion, manipulation, and saving CSV files.

scikit-learn – Employed for the following preprocessing steps:

SimpleImputer: Fills missing values in both numerical and categorical fields.

StandardScaler: Standardizes numeric features to have mean = 0 and variance = 1.

OneHotEncoder: Encodes categorical variables into binary columns.

ColumnTransformer: Selectively applies transformations to numeric and categorical columns.

Pipeline: Creates a streamlined processing sequence.

🔁 ETL Pipeline Workflow

Extract
The pipeline reads data from a CSV file (or creates a sample file if missing).

pandas is used to load the data into a DataFrame.

Transform
Missing numeric values are replaced with column means.

Missing categorical values are filled with the most frequent category.

Categorical columns are converted to one-hot encoding.

Numeric columns are scaled using standardization.

All transformations are applied using ColumnTransformer for modularity.

Load
The transformed NumPy array (sparse or dense) is saved back to data.csv using pandas.

💻 How to Run

Make sure Python and required libraries (pandas, scikit-learn) are installed.

Place the datapipeline.py script inside your project directory.

Open the script in VS Code and run it.

Output will be saved in data.csv in the same directory.

✅ Output

The final output file (data.csv) contains transformed numeric and categorical data in machine-learning-ready format.

The column structure depends on the encoding and scaling process applied by the scikit-learn pipeline.

🚀 Future Enhancements

Incorporate logging functionality for debugging and monitoring.

Add support for reading from and writing to databases.

Integrate with cloud storage or scheduled batch processing using tools like Apache Airflow or Prefect.

Extend transformation logic with feature engineering.

📌 Summary

This project offers a foundational understanding of building a modular and automated ETL pipeline using open-source Python libraries. The datapipeline.py script provides clear, maintainable, and reproducible

data processing logic suitable for both beginners and intermediate practitioners in data engineering and machine learning.

#output
[data1.csv](https://github.com/user-attachments/files/20809800/data1.csv)
