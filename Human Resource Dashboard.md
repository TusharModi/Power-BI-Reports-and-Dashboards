# Human Resource Dashboard

### Dashboard Link: https://app.powerbi.com/view?r=eyJrIjoiYTkzNmJlNTAtNTYxNi00OTgyLWJlMzctMDA2MjkzNzZhYmM3IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9

## Problem Statement
The Human Resource dashboard provides a comprehensive view of salary and employee details. Its primary purpose is to streamline the management of HR data by offering visualizations and insights into various aspects of employee compensation and staffing.
Key purposes of this dashboard include:
1.	Salary Analysis: Visualizes salary distributions across different departments, roles, or levels within the organization. This helps identify trends, anomalies, and areas for salary adjustments.
2.	Employee Overview: Displays detailed information about employees, such as their roles, tenure, and compensation packages. This aids in understanding workforce composition and planning.
3.	Decision-Making Support: Facilitates informed decision-making by providing easy access to critical HR metrics and data points. For instance, it can assist in budgeting, salary benchmarking, and workforce planning.
4.	Performance Tracking: Helps track and manage employee performance and compensation over time, providing insights into the effectiveness of HR policies and compensation strategies.
5.	Data Visualization: Utilizes charts, graphs, and tables to present complex data in an easily understandable format, enabling HR professionals and management to quickly grasp key information.
Overall, the dashboard serves as a valuable tool for HR professionals to monitor and analyze employee and salary data, improving efficiency and supporting strategic HR decisions.

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except columns.
- Step 5 : In the report view, under the view tab, theme was selected.
- Step 6 : A new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 7 : card visual was added to the canvas, representing total salary cost, total employees, total active employees, total sick days and balance days.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into total salary cost, total employees, total active employees, total sick days and balance days.
           Although, by default, while calculating total sales, blank values are ignored.

![Cards](https://github.com/user-attachments/assets/e1ad841a-bc2e-4b08-b39a-0bbb1357a246)

- Step 8 : A bar chart was also added to the report design area representing the total sick days by year and quater. 
![Bar](https://github.com/user-attachments/assets/e0e0eff2-d582-4d2a-bb61-32dc4cbecf6b)

- Step 9 : Different slicers are used to filter the data on this page.

![Slicer](https://github.com/user-attachments/assets/5e9795da-ab75-4d9a-ae25-66b360f1aa9c)

 - Step 10 : The donut chart displays various information, such as gender, job type, and other details.

![Donut](https://github.com/user-attachments/assets/9262802b-c7cf-4dc0-9e52-14311e46e278)

 - Step 11 : The report was then published to Power BI Service.
 
# Snapshot of Dashboard

![First](https://github.com/user-attachments/assets/f69ba312-84ea-4816-bcf5-8b390441810b)

![Second](https://github.com/user-attachments/assets/6cdff59c-9861-4bb2-b783-ca1edd20f19e)

![Thrid](https://github.com/user-attachments/assets/122de76d-5e22-48ed-99c6-9ac0f791982b)
