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


![Image Alt Text](https://github.com/Anqa-H/End-to-End-Data-Pipeline-using-Google-Cloud-Data-Fusion-BigQuery-Looker-/blob/557b6f6e78abba6e709a35b431fb23c0b774f0ff/GCP.drawio.png)


Data Generation:
Used the Faker library to generate realistic employee data for the pipeline.

Data Upload:
Uploaded the generated CSV file to a Google Cloud Storage bucket.

Data Ingestion:
Extracted the CSV file from Cloud Storage into Data Fusion.

Data Transformation & Masking:
Used Data Fusion Wrangler to clean and mask sensitive information.

![Image Alt Text](https://github.com/Anqa-H/End-to-End-Data-Pipeline-using-Google-Cloud-Data-Fusion-BigQuery-Looker-/blob/20d281eab33b303a068aac2eebebc482ee42b0bb/Screenshot%202024-10-19%20171838.jpg)


![Image Alt Text](https://github.com/Anqa-H/End-to-End-Data-Pipeline-using-Google-Cloud-Data-Fusion-BigQuery-Looker-/blob/7893d952813479a0babe697e46f6e5cb39730e6e/Screenshot%202024-10-19%20171702.jpg)


Pipeline Automation: Automated the pipeline in Data Fusion to run monthly.


![Image Alt Text](https://github.com/Anqa-H/End-to-End-Data-Pipeline-using-Google-Cloud-Data-Fusion-BigQuery-Looker-/blob/03866b2a609d1a401b1168c2f371fdd50a67ed2d/Screenshot%202024-10-19%20182426.jpg)


Data Storage:
Loaded the masked data into a BigQuery table for secure storage and analysis.

Pipeline Automation:
Scheduled the pipeline in Data Fusion to automatically run once a month.

Data Visualization & Reporting:
Connected BigQuery to Looker to design interactive dashboards, enabling insightful reporting and data-driven decision-making.
