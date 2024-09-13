# Purchase Lines Dashboard

### Dashboard Link: https://app.powerbi.com/view?r=eyJrIjoiZTIxMDg0NTEtMTI0ZS00ZjllLWFiZDQtYTg0NDcxMjQ1ZTAwIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9

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
- Step 7 : One card visual was added to the canvas, representing total amount, total open amount, total purchase orders and total open lines.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into total amount, total open amount, total purchase orders and total open lines.
           Although, by default, while calculating total sales, blank values are ignored.
![cards](https://github.com/user-attachments/assets/fc503fb2-ed93-41aa-aac8-d31814c378d7)
- Step 8 : A bar chart was also added to the report design area representing the total lines number by region and total purchase order by monthly.
![Bars](https://github.com/user-attachments/assets/ddc6f03a-69ed-43fe-94d9-99137da7bf8c)

- Step 9 : The table shows purchase order details, allowing the end user to easily understand how each PO line is open or closed.
![PO Line](https://github.com/user-attachments/assets/878c2968-1853-47c8-a158-0ad951445940)
  - Step 10 : The decomposition tree shows organizational information based on the total amount, and it is expandable.
![Decom](https://github.com/user-attachments/assets/7c34b9be-d1a3-46b2-b783-1882183f2209)
  - Step 11 : The purchase line statuses are shown in a donut chart.
![Line status](https://github.com/user-attachments/assets/c3bfa021-cf2a-499f-a9e2-b3447b957a96)
- Step 12 : The report was then published to Power BI Service.
# Snapshot of Dashboard
![Purchase Lines](https://github.com/user-attachments/assets/0eed5ae9-a0b1-4b4c-8e9c-1aaef3cf12cb)
