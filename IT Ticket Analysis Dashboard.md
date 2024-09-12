# IT Ticket Analysis Dashboard

### Dashboard Link: https://app.powerbi.com/view?r=eyJrIjoiOTdjYWI2MGEtMzhkYi00YjAwLTgxNTAtODk0MGY0NjY4Y2IzIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9

## Problem Statement

This dashboard helps IT Ticket Analysis by providing insights into the number of closed tickets, their priorities, and severities. It tracks key metrics related to total tickets, total days, total users, and total departments. By using this dashboard, the Head of IT can identify how many tickets are closed and assess their priorities and severities. This dashboard serves as a template, and the datastore can be downloaded from Kaggle. It showcases my skills in data analysis and visualization.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except columns.
- Step 5 : In the report view, under the view tab, theme was selected.
- Step 6 : A new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 7 : Multiple card visual was added to the canvas, representing total users, total tickets, total days, total departments and avg. Res. Days.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into total users, total tickets, total days, total departments and avg. Res. Days that how to improve IT Ticket Analysis.
           Although, by default, while calculating total respondents, blank values are ignored.

![cards](https://github.com/user-attachments/assets/cf98a2de-0a4e-4d37-993b-ddf8be7178da)

- Step 8 : A donut chart was also added to the report design area representing severity, priority, ticket type and gender.

![Ser](https://github.com/user-attachments/assets/17ed67e4-7bcc-4907-955d-f5f3e18c8e2b)

- Step 9: The report was then published to Power BI Service.
 
# Snapshot of Dashboard

![IT Ticket](https://github.com/user-attachments/assets/eb27c178-b3c3-473a-9107-b8d8571e2deb)
