README: Data Analysis Project

This repository contains the code and resources for a data analysis project focused on assessing the basic infrastructure of schools in Brazil, leveraging the 2024 School Census data. This project demonstrates skills in data engineering, data analysis, and cloud computing.

Project Overview
The main objective of this project is to identify and visualize the gaps in basic infrastructure (water, electricity, and sanitation) in Brazilian schools. By analyzing official data, the project provides valuable insights that can inform strategic decisions and resource allocation to improve the learning environment for children.

Key Features
Data Source: The project uses the official 2024 School Census microdata, a comprehensive dataset provided by the Brazilian Ministry of Education (MEC).
Cloud-Native Architecture: The entire data pipeline is built and executed on Microsoft Azure, showcasing proficiency with key cloud services:
Azure Blob Storage: Used to store the raw CSV dataset, ensuring secure and scalable data residency in the cloud.
Azure Databricks: A powerful, cloud-based platform for data analytics and Machine Learning. Databricks is used to run the Python code, demonstrating an understanding of professional data environments.

Data Analysis & Visualization
The project uses the Python libraries pandas, matplotlib, and seaborn to perform data cleaning, aggregation, and to generate insightful visualizations. The final output includes:
A bar chart showing the percentage of schools lacking basic infrastructure (water, electricity, and sanitation) nationwide.
A regional breakdown, with bar charts illustrating infrastructure deficiencies per state (UF).

Why This Matters
This project directly addresses a critical issue in education and child development. By identifying schools in need, the analysis can help organizations like UNICEF to:
Prioritize regions for intervention and investment.
Monitor the progress of infrastructure projects over time.
Provide data-driven evidence to policymakers.
This approach demonstrates the ability to translate a real-world problem into a data science solution, a key skill for a successful career in this field.

How to Run the Project
Azure Setup: Ensure you have an Azure account with an active Databricks workspace and a Storage Account.
Upload Data: Upload the microdados_ed_basica_2024.CSV file to a container in your Azure Blob Storage.
Run the Notebook:
Open the Databricks notebook.
Fill in your Azure Storage Account details and access key.
Attach the notebook to an active Databricks cluster.
Execute the notebook to see the analysis and visualizations.



### Project Data
The original dataset is available for download at this link: https://storageschoolanalysis.blob.core.windows.net/eof-raw/microdados_ed_basica_2024.csv?sp=r&st=2025-08-22T18:53:38Z&se=2025-11-01T02:59:59Z&spr=https&sv=2024-11-04&sr=b&sig=Ni5%2FsOp2Jwxq7YBbtecw4XU5%2Bj16%2BVNLptkDyW5Xw8M%3D
