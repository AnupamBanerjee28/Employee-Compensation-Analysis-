# Employee-Compensation-Analysis
This project provides a comprehensive business intelligence solution for analyzing historical employee compensation data, focusing on trends, geographical disparities, and departmental metrics.

## Project Goal
To transform raw historical HR data into actionable executive insights using an interactive Power BI dashboard, enabling data-driven decision-making regarding pay equity, resource allocation, and compensation strategy.


## Key Features

- **Interactive Dashboard:** A dynamic Power BI report allowing filtering by year, department, job title, and compensation type.
- **Trend Analysis:** Visualizing changes in Base Salary, Bonuses, and Benefits from 2018 to 2024.
- **Geographic Variance:** Mapping and comparing total compensation packages across different global and domestic locations.
- **Compensation Equity:** Defining and tracking KPIs to measure and report on potential pay gaps within the organization.


## Tools and Technologies Used

The project utilizes several key tools and technologies.

- **Power BI** is used as the main platform for creating dashboards and reports. 
- For **data transformation(ETL)**, **Power Query (M Language)** helps in cleaning, shaping, and integrating the raw CSV data. 
- **Data modeling** is carried out using **DAX(Data Analysis Expressions)**, allowing the development of calculated columns, complex measures, and defining key performance indicators(KPIs).
- The **source data** is stored in **CSV (Excel/Text) format**, serving as the initial input for the analysis.


## Data Analysis Process

**1.	Data Ingestion & Cleaning:** Loaded the employee_dataset_2018_2024.csv into Power BI. Applied ETL logic using Power Query to handle data type conversions, structure the date column, and ensure data quality.

**2.	Dimensional Modeling:** Established a star schema model, linking compensation facts (Salary, Bonus, Benefits) to dimensions (Employee, Date, Location, Department).

**3.	KPI Definition:** Developed DAX measures for analytical reporting.

**4.	Visualization:** Designed visually appealing and mobile-responsive charts (bar charts, line graphs, scatter plots, and slicers) to present the key findings effectively.

**5.	Deployment:** The final .pbix file (Employee Compensation.pbix) is ready for deployment to Power BI Service for sharing with stakeholders.


**Screenshot:**
