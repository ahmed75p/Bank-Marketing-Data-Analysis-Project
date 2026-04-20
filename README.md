📊 Bank Marketing Data Analysis Project


🧠 Project Overview

This project analyzes a bank marketing dataset to understand customer behavior and improve term deposit subscription rates.

To simulate a real-world data environment, the dataset was split into three different data sources:

CSV files
TXT files
SQL Database

This was done to mimic how data is usually stored across multiple systems in real business environments.

📥 Dataset Source

Original dataset is publicly available on Kaggle:
🔗 https://www.kaggle.com/datasets/your-dataset-link

🏗️ Project Architecture
                ┌──────────────┐
                │   CSV Files  │
                └──────┬───────┘
                       │
                ┌──────▼───────┐
                │   TXT Files  │
                └──────┬───────┘
                       │
                ┌──────▼────────────┐
                │ SQL Server DB     │
                └──────┬────────────┘
                       │
               ┌───────▼───────────┐
               │   SSIS ETL        │
               └───────┬───────────┘
                       │
               ┌───────▼───────────┐
               │ Data Warehouse     │
               └───────┬───────────┘
                       │
               ┌───────▼───────────┐
               │ Power BI Dashboard │
               └────────────────────┘
⚙️ Tools & Technologies
SQL Server
SSIS (ETL)
Power BI
Excel / CSV / TXT Data Sources
🚀 How to Run the Project
Clone the repository
Restore the SQL Server database
Open SSIS project in Visual Studio
Update all file paths in Flat File Connections
Run ETL packages to load data into Data Warehouse
Open Power BI file and refresh data source
⚙️ Deployment Note

In a real-world scenario, the ETL pipeline would be deployed and scheduled using SQL Server Agent for automated data refresh.
However, this project focuses on building an end-to-end analytical system rather than production deployment.

🖼️ Dashboard Preview

Add your images here:

![Overview](Images/overview.png)
![Customers](Images/customers.png)
![Campaign](Images/campaign.png)
📊 Key Insights
Overall subscription rate is ~22.6%
Age (28–61) is common but not a strong driver
Demographics like marital status and education have low impact
Retired customers and students show highest conversion (~30%+ and ~43%)
Previous campaign success is the strongest predictor (65% vs 14%)
More contact attempts reduce conversion rate
Longer call duration is linked to higher conversion
🚀 Recommendations
Focus on high-performing segments (retired & students)
Prioritize customers with positive previous campaign outcomes
Reduce excessive contact attempts
Improve quality of customer interactions
Use personalized and data-driven targeting instead of generic campaigns
Avoid relying on weak features like marital status and education
📌 Final Summary

This project demonstrates an end-to-end data pipeline including data integration from multiple sources, 
ETL processing, data warehousing, and business intelligence dashboards to support data-driven decision making in banking marketing campaigns.


👤 Author

Ahmed Mostafa
📧 Email: your-email@gmail.com

🔗 GitHub: https://github.com/your-username
