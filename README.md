🛒 Omnichannel Sales & ETL Data Transformation Dashboard

<img width="1917" height="1111" alt="image" src="https://github.com/user-attachments/assets/39d917a3-bb1f-4aaf-b8d9-f2eab33d1bdc" />


📝 Project Overview

This project focuses on the ETL (Extract, Transform, Load) process. A major challenge in Business Intelligence is dealing with siloed, inconsistently formatted data across different business units.

The objective of this project was to extract raw sales data from three completely different platforms (Web, Mobile App, and Marketplace), clean the inconsistencies, append them into a single unified data model, and visualize the omnichannel performance in Power BI.

🛠️ Technical Skills Demonstrated

Advanced Power Query (M): * Extracted and profiled data from three disparate sources.

Appended multiple queries into a single All_Sales master fact table.

Data Cleaning & Standardization:

Resolved severe data type conflicts across tables.

Handled complex Date formatting issues where different systems exported dates in conflicting locales (e.g., YYYY/MM/DD vs DD-MM-YYYY vs DD-MMM-YYYY) by applying Locale transformations and text-replacement techniques prior to appending.

Data Visualization: * Designed a unified dashboard to compare channel performance, highlighting revenue distribution across Web, App, and Marketplace.

📂 Repository Contents

App_Sales.csv, Web_Sales.csv, Marketplace_Sales.csv: The raw, inconsistently formatted datasets.

Omnichannel_Sales_Dashboard.pbix: The finalized Power BI file containing the cleaned data model and visualizations.

Designed and developed by [ MOHAMMAD DANIYAL USMAN ]
