# Sales Analytics

📂 Main Attributes & Capabilities 

Data Cleansing & Conversion: 
Imported and verified structured CSV sales data into PySpark DataFrames. 
Implemented filters to exclude entries with incorrect quantity and pricing information. 
Calculated new features such as total_sales and identified time-related dimensions (e.g., month). 

Dynamic Monthly Sales Evaluation: 
Combined monthly sales from various regions by utilizing groupBy and sum functions. 
Utilized date_format() and date modifications to facilitate monthly trend examination. 

Sophisticated SQL Methods: 
Employed Common Table Expressions (CTEs) via linked DataFrame transformations to organize intricate queries. 

Utilized Window Functions to compute: 
Total cumulative runs by region. 
Month-to-Month (MoM) growth rate as an essential performance indicator. 

Ranking of Products by Region: 
Determined the highest-selling item in every region by applying ranking functions on partitioned data. 
Utilized rank() with a descending order on total product sales to gain insights into regional customer preferences. 

Engaging & Multi-Faceted Visual Representations: 
Developed interactive line graphs using Plotly to monitor monthly sales trends and highlight MoM growth percentages. 
Employed bar graphs to display the top revenue-producing products by region. 
Created a heatmap with Seaborn to analyze sales performance across different regions and months. 

Expandable & Modular Structure: 
Developed code to be modular for improved readability, testing, and expansion. 
Configured the system for smooth operation on Google Colab, guaranteeing scalability without needing local installation. 

📊 Business Worth & Understanding 

Facilitated analysis of regional sales trends to inform strategic marketing and resource distribution. 
Provided performance metrics (e.g., MoM growth) to help stakeholders assess sales momentum. 
Pinpointed high-performing products by region to aid in focused promotions and inventory management. 
Enabled immediate decision-making via engaging and visually appealing dashboards. 


Colab : https://colab.research.google.com/drive/1zy8Y080SuWj50lAdeE8CH1Lkpd_4ZX_D?usp=sharing
