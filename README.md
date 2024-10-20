# End-to-End-Data-Pipeline-using-Google-Cloud-Data-Fusion-BigQuery-Looker-
End-to-End Data Pipeline using Google Cloud (Data Fusion, BigQuery, Looker)

Project Overview:
I created this project to extract employee data from various sources, mask sensitive information, load it into BigQuery, and develop a dashboard to visualize the data.

Requirements:

Data Extraction: Retrieve employee data from multiple sources.
Data Masking: Mask sensitive information like salaries and personal data to ensure data privacy.
Data Loading: Securely load the masked data into BigQuery.
Dashboard Visualization: Develop a web-based dashboard using Looker to visualize the employee data.
Solution:

Data Generation:
Used the Faker library to generate realistic employee data for the pipeline.
Data Upload:
Uploaded the generated CSV file to a Google Cloud Storage bucket.
Data Ingestion:
Extracted the CSV file from Cloud Storage into Data Fusion.
Data Transformation & Masking:
Used Data Fusion Wrangler to clean and mask sensitive information.
Data Storage:
Loaded the masked data into a BigQuery table for secure storage and analysis.
Pipeline Automation:
Scheduled the pipeline in Data Fusion to automatically run once a month.
Data Visualization & Reporting:
Connected BigQuery to Looker to design interactive dashboards, enabling insightful reporting and data-driven decision-making.
