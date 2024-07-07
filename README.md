# **Customer Churn Anlysis: A Machine Learning Approach To Classification Models**

 In this project, we focus on building classification models to perform churn analysis on customer data, a critical task for companies looking to enhance their revenue by retaining customers.

**Data Sources**
 In this project, the dataset is spread across three different sources:

First Data Set: The initial 3000 records of the dataset are stored in a remote SQL database. You will need to access this database to gather the data.

Second Data Set: The next 2000 records are available on OneDrive in an Excel file named "Telco-churn-second-2000.xlsx". This dataset serves as the test dataset.

Third Data Set: The final portion of the data, comprising 2000 records, is hosted on this GitHub Repository in a CSV file named "LP2_Telco-churn-last-2000.csv". Additional information about the dataset's features and context can also be found in this repository.


**Project Workflow**
Data Collection: Customer data was collected from various sources, including SQL Server tables and CSV/Excel files, covering demographics, services, payment, and churn status.

Data Processing: Collected data was transformed into a suitable format using libraries like pyodbc and pandas, creating a comprehensive dataset.

Exploratory Data Analysis (EDA): Extensive EDA was performed, including data summarization, handling missing values, and univariate and bivariate analyses, using pandas, numpy, matplotlib, and seaborn.

Data Preprocessing: Data was cleaned, missing values handled, and categorical variables transformed, making it ready for in-depth analysis with pandas.

Hypothesis Testing: Hypotheses on customer churn were formulated and tested using various statistical methods, including scipy's hypothesis tests.

Visual Insights: Compelling visualizations were created to answer analytical questions about customer churn.

Data Balancing: Class imbalance was addressed using the SMOTETomek technique.

Model Training and Evaluation: Multiple machine learning models were trained, evaluated, and assessed, using classification reports with F1-score as the evaluation metric.

Model Fine-Tuning: The best-performing model was fine-tuned as needed.

Advanced Model Improvement: Hyperparameter tuning was performed for selected models using GridSearchCV.

Future Predictions: The trained model can be deployed for ongoing predictions on new data, allowing proactive measures for customer retention.

Power BI Deployment: Analysis and visuals were deployed in Power BI for interactive exploration and sharing.


**Conclusion**
Through a combination of data preprocessing, feature engineering, and model training, we successfully built a model that achieved a good accuracy score. This indicates our model's ability to effectively differentiate between loyal customers and those at risk of churning. This information can help businesses take proactive measures to retain customers and improve customer satisfaction.