# Purchase Lines Dashboard

Dashboard Link: https://app.powerbi.com/view?r=eyJrIjoiNGQ2MTk4YmItOWUwNS00NjJmLTk5MWQtYmNkNDFkMjcxYTA0IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9

## Problem Statement
This dashboard helps the purchasing team better understand their open purchase orders. It provides insights into which purchase orders are open, closed, or completely closed. It's similar to ordering a product online: after placing an order, a request number is generated, and various processes occur, such as warehouse dispatch. Although the product might leave the warehouse, the order is not considered closed until it reaches its final destination. The same concept applies to purchase lines in the supply chain.
The dashboard also shows purchases by different states. By using this dashboard, the head of the department can identify how many lines are open or closed, enabling higher management to make informed decisions. This is a dummy dataset and serves to demonstrate my data visualization skills.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except columns.
- Step 5 : In the report view, under the view tab, theme was selected.
- Step 6 : A new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 7 : card visual was added to the canvas, representing total amount, total open amount, total purchase orders and total open lines.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into total amount, total open amount, total purchase orders and total open lines.
           Although, by default, while calculating total sales, blank values are ignored.
  
![Cards](https://github.com/user-attachments/assets/379a3ed4-410f-4c5e-96ac-23dc221911ef)

- Step 8 : A bar chart was also added to the report design area representing the total lines number by region and total purchase order by monthly.
  
![Bar Chart](https://github.com/user-attachments/assets/28b7a540-111e-4f6d-93f8-5b54eb32cc08)

- Step 9 : The table shows purchase order details, allowing the end user to easily understand how each PO line is open or closed.
  
![Table](https://github.com/user-attachments/assets/3e4410bf-dc8a-484b-8e33-e8dd5171cfa4)

- Step 10 : The decomposition tree shows organizational information based on the total amount, and it is expandable.
  
![Decomp](https://github.com/user-attachments/assets/0c622fcd-6799-4774-bf12-20534182ca4a)

- Step 11 : The purchase line statuses are shown in a donut chart.
  
![Dount](https://github.com/user-attachments/assets/70cd2653-3704-466a-b579-69697da2888c)

- Step 12 : The report was then published to Power BI Service.
# Snapshot of Dashboard

![Purchase](https://github.com/user-attachments/assets/39276ddc-b1ba-48d3-bd38-bb59275106bd)
