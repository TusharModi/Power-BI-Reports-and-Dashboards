# Delicious Pizza Dashboard

### Dashboard Link: https://app.powerbi.com/view?r=eyJrIjoiYmIwNGQyMzItMzE3My00ZTVmLThlYTktZTAxNmQ5NzNlZDM1IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9

## Problem Statement

This dashboard helps the pizza shopkeeper better understand their sales. It provides insights into which pizzas are selling more and breaks down sales by province. It also shows revenue by different states and stores. By using this dashboard, the shopkeeper can identify trends and issues, allowing them to address factors contributing to increased sales.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except columns.
- Step 5 : In the report view, under the view tab, theme was selected.
- Step 6 : A new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 7 : One card visual was added to the canvas, representing total sales by province.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into total sales.
           Although, by default, while calculating total sales, blank values are ignored.
- Step 8 : A bar chart was also added to the report design area representing the total sales of  days & target.
  
![Target and sales amounts by day](https://github.com/user-attachments/assets/2baa72db-eb1a-408d-9404-010e7927ab5f)

- Step 9 : New measure was created to find total sales of stores.
        
A card visual was used to represent Total Sales.

![Total Sales](https://github.com/user-attachments/assets/3e89431d-f384-4561-afbe-42ad290b881d)
 - Step 10 : New measure was created to find  sales amount of pizza type,
 
 A bar visual was used to represent this sales amount of pizza type.
 
 Snap of sales amount of pizza type
 
![Bar](https://github.com/user-attachments/assets/2a93a84e-5722-402d-85aa-fe50012717e6)

 - Step 11 : The report was then published to Power BI Service.
 
# Snapshot of Dashboard
![Delicious Pizza](https://github.com/user-attachments/assets/2831ebc8-bf74-4926-ab83-2c72f32ced7e)
