# Hotel-Finance-Dashboard_SM
The Hotel Finance Dashboard is a data-driven tool focused on understanding trends in financial revenue within the KROWN Hotels Group. This interactive dashboard provides functionality for navigating finance and enables the stakeholders to optimize their revenue and customer retention strategies efficiently. The dashboard breaks down crucial data-driven insights and presents a call to action based on these insights. 

## Objective
The primary objective is to provide stakeholders with a comprehensive financial performance overview, an in-depth report of the data, and potential recommendations. Visualizing the sales data through a dashboard enhances decision-making and strategic planning by giving crucial insights into customer behavior, sales trends, and product performance.

## Dataset
The dataset comprises hotel data with crucial booking details like market segment, adr, customer information, lead times, and cancelations. Other dependencies include distribution channel, hotel type, and expenses. The dataset was initially part of a revenue tracker in KROWN Hotel's database updated daily. Then the dataset was imported to SQL Server Management Studio (SSMS) to calculate KPIs and perform data transformation. The database server was then connected to Power BI to clean and transform. The structural procedure was automated with a daily recurring job task, allowing it to integrate into a fully functional automated real-time dashboard. 

## Features
  - Interactive Visualizations: The dashboard offers interactive visualizations such as line charts, bar charts, and pie charts, allowing users of all backgrounds to explore finance data.

  - Key Performance Indicators (KPIs): Important metrics such as total revenue, average adr, total cancelations, and total bookings are highlighted for easy monitoring.

  - Filtering and Drill-Down: Users can filter data by date, market segment, and customer type to drill down into specific insights.

  - Data Cleaning and Transformation: Raw data from the Revenue Tracker was transformed using SQL Server Management Studio, Power BI, and DAX formula ensuring data integrity and consistency before integration.

  - Report: The dashboard provides a report along with recommendations, providing insights into the financial performance.

  - Automated Real-time Insights: The dashboard is automated by creating a recurring job task in SSMS and importing the real-time data source from the SQL Server Database to Power BI.

## Dashboard
Finance Dashboard

![Overview](https://github.com/user-attachments/assets/9617ca7c-b051-4821-bc98-fe2b475d9943)

![Overview-icon](https://github.com/user-attachments/assets/7b363782-8fa8-4ee0-80fa-21e33d3651ef)

![Revenue](https://github.com/user-attachments/assets/439a691e-4eec-4cba-8f4f-2044b4a7d3e5)

![Cancelation](https://github.com/user-attachments/assets/6ac195e2-a140-46a5-b9d4-b7fb32de525e)

![Report](https://github.com/user-attachments/assets/ffda0731-377c-4264-ab74-5dfd88a9b5ac)




<span style='font-size: small'>Copyright © 2024 Samee Manidhar. All Rights Reserved.</span>
