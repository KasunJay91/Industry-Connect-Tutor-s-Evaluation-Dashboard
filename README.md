Tutor's Evaluation Dashboard for Industry Connect - BI Analyst Project


![Tutor's Evalution Dashoard](https://github.com/user-attachments/assets/e1261dcf-3965-46c9-917b-33003cabaa4e)

Overview

As a BI Analyst at MVP Studio, I successfully delivered a comprehensive Tutor Evaluation Dashboard for Industry Connect, a key external stakeholder. The project aimed to evaluate tutor performance, and the effectiveness of training materials based on student feedback collected at regular intervals. The stakeholders required detailed insights into tutor performance, program effectiveness, and trends across multiple intakes to make informed decisions for enhancing the overall learning experience.
This project involved designing a robust data pipeline using Fabric Lakehouse and Azure Data Factory, building a scalable Star Schema data model, and creating interactive dashboards with advanced DAX functions in Power BI. The dashboard also featured drill-through capabilities for deeper analysis, and formal paginated reports were generated using SQL Server Reporting Services (SSRS).
________________________________________
Project Environment and Workflow
•	Environment: Lakehouse in Microsoft Fabric
•	Data Source: Feedback data collected via Google Forms and stored in three Google Sheets (week_1_2_responses, week_3_4_responses, week_5_6_responses).
•	ETL Pipeline: Built using Azure Data Factory to automate data extraction, transformation, and loading into the Lakehouse.
•	Data Modelling: Designed a Star Schema with staging tables, dimension tables (Dim_Tutor, Dim_Program, Dim_Responses), and a fact table.
•	Visualization: Developed an interactive Power BI dashboard, utilizing drill-through navigation and advanced DAX calculations.
________________________________________
Project Requirements and Deliverables
1.	Stakeholder Requirements:
o	Comprehensive insights into tutor performance, including the number of responses and average ratings.
o	Detailed program performance analysis by intake, including trends in student satisfaction and training material ratings.
o	Calculation and visualization of the Net Promoter Score (NPS), with breakdowns of promoters, passives, and detractors.
o	Drill-through options to explore individual scores and comments for each response.
o	Comparative analysis of ratings across tutors, programs, and intakes.
2.	Data Integration:
o	Merged the three Google Sheets into a single dataset using Fabric Lakehouse.
o	Applied transformations to clean and structure the data, appending all sheets into a unified table.
3.	Data Modelling:
o	Separated the unified dataset into three dimension tables (Dim_Tutor, Dim_Program, Dim_Responses) and one fact table.
o	Designed the data model to support flexible querying and optimised performance for BI reporting.
4.	Advanced Analytics and Visualisation:
o	Used advanced DAX functions (e.g., CALCULATE, SUMX, FILTER) to create calculated measures for KPIs such as average tutor ratings, NPS, and intake comparisons.
o	Enabled drill-through capabilities to navigate between detailed views of tutor performance and program-specific insights.
o	Created interactive slicers for filtering by program, intake, and tutor to enhance stakeholder exploration.
o	Designed custom visuals to highlight key metrics, including:
	Average training skills and helpfulness ratings by tutor.
	Program-specific NPS and satisfaction trends.
	Ratings and responses comparison by intake and program.
5.	Paginated Reporting:
o	Delivered detailed paginated reports using SSRS, providing formal documentation of tutor performance metrics.
o	Ensured reports were exportable to multiple formats (PDF, Excel) for broader distribution.
________________________________________
Tools & Technologies Used
•	Fabric Lakehouse: For data integration and modelling.
•	Azure Data Factory: For automating the ETL pipeline.
•	Power BI: For advanced analytics and interactive dashboard creation.
•	DAX Functions: For complex calculations and KPI creation.
•	SSRS: For creating paginated reports.
•	Google Sheets API: For data extraction.
•	SQL: For data transformation and querying.
________________________________________
Outcomes
•	Delivered a dynamic, user-friendly dashboard tailored to stakeholder requirements, enabling real-time monitoring of tutor performance and program effectiveness.
•	Enhanced decision-making with actionable insights into training material quality, tutor helpfulness, and student satisfaction across intakes.
•	Simplified reporting processes through automation and seamless integration between tools.
•	Provided stakeholders with the ability to drill into detailed data and conduct intake-to-intake comparisons effortlessly.
•	Streamlined external communication and documentation with formal paginated reports.
________________________________________
This project exemplifies my expertise in data integration, modelling, advanced analytics, and BI solutions development. It highlights my ability to deliver end-to-end solutions that transform raw data into actionable insights, meeting and exceeding stakeholder expectations.
