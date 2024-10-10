# Churn_Predictor

Churn Analysis Dashboard with Machine Learning Prediction

This project demonstrates the development of a comprehensive churn analysis dashboard using Power BI. The dashboard leverages historical customer data to not only visualize key churn metrics but also predict future churn probability using a machine learning model.

My Contribution:

In this project, I implemented the entire ETL (Extract, Transform, Load) process, built the Power BI data model and visualizations, and trained a machine learning model to predict customer churn.

Steps:

Data Acquisition and Preparation (ETL):
Source: Downloaded a sample customer dataset (replace with details of your data source).
Database Setup: Created a SQL Server database (or used another database management system) and a table to store the customer data (Screenshot 1: Show your database table structure).
Data Import: Imported the customer data from the source file into the database table using the appropriate import method (Screenshot 2: Show the data import process).
Power BI Data Model:
Power BI Desktop: Launched Power BI Desktop and created a new report.
Data Connection: Established a connection between Power BI and the SQL Server database containing the customer data (Screenshot 3: Show the process of connecting Power BI to your database).
Data Model Creation: Defined the relationships between tables within the data model (if applicable to your data).
Measures: Created calculated measures in Power BI to analyze key metrics such as:
Total number of customers
Total number of new customers (joiners)
Total number of churned customers
Churn rate (percentage of customers who churned)
Dimensions: Created dimensions to group and analyze the data by various categories such as:
Demographics (e.g., age, gender)
Account details (e.g., payment method, contract type, tenure)
Geographic location (e.g., state)
Churn distribution (e.g., churn category, reason for churn)
Services used by customers
Data Visualization:
Dashboard Design: Created a visually appealing and informative dashboard with multiple pages to display various insights.
Summary Page: Designed a summary page showcasing the overall customer churn situation with key metrics like total number of customers, churn rate, etc. (Screenshot 4: Show your summary page visualization).
Demographic Page: Developed a page visualizing the distribution of customers based on demographic factors like age and gender (Screenshot 5: Show your demographic page visualization).
Account Page: Created a page displaying customer account details like payment methods, contract types, and tenure (Screenshot 6: Show your account page visualization).
Geographic Page: Designed a page visualizing the geographic distribution of customers (e.g., by state) (Screenshot 7: Show your geographic page visualization).
Churn Distribution Page: Created a page that analyzes the churn distribution, categorizing churn and displaying reasons for churn (Screenshot 8: Show your churn distribution page visualization).
Services Page: Developed a page visualizing the services utilized by customers (Screenshot 9: Show your services page visualization).
Machine Learning Model for Churn Prediction:
Model Selection: Implemented a Random Forest model (or another suitable algorithm) to predict customer churn probability based on historical data.
Model Training: Trained the model using the historical customer data, focusing on features that might indicate churn propensity.
Model Evaluation: Evaluated the model's performance using appropriate metrics to assess its effectiveness in predicting churn.
Prediction Integration: Integrated the trained model into the Power BI dashboard to predict churn probability for new customers.
Churn Profile Page:
New Customer Analysis: Created a dedicated page displaying the predicted churn probability for new customers.
Information Display: Included customer ID, name, predicted churn probability, and other relevant information on the page (Screenshot 10: Show your churn profile page visualization).
Key Takeaways:

This project demonstrates the power of combining data analysis and machine learning to gain valuable insights into customer churn. The interactive Power BI dashboard allows for comprehensive churn analysis, enabling businesses to proactively identify customers at risk of churning and implement retention strategies.   

Further Enhancements:

Explore the use of different machine learning algorithms for churn prediction and compare their performance.
Integrate real-time data into the dashboard to provide up-to-date insights.
Develop alerts or notifications within the dashboard to trigger actions for high-risk churn customers.
