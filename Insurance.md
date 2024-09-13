# Insurance Dashboard
## Problem Statement
This dashboard helps showcase commodity insurance across CRPS, logistics, and mobile insurance, as well as health insurance. It allows the insurance team to better understand their claim statuses, including accepted claims and total claims. It provides insights into which insurance products are more in demand in the market.
The dashboard also displays details of multiple insurance policies. By using this dashboard, the COO can identify which insurance policies are more in demand and recognize older policies where the company can make improvements to attract more customers. Based on this information, the COO can make strategic decisions. This is a dummy dataset and serves to demonstrate my data visualization skills. The main purpose of this dashboard is to serve as a proof of concept. Here, I have demonstrated the functionality, but the numbers may be incorrect.

I have created two templates and attached screenshots of them in this blog.

## Template 1

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except columns.
- Step 5 : In the report view, under the view tab, theme was selected.
- Step 6 : A new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 7 : Card visuals were added to the canvas, representing total claims, total accepted claims, and total claims by month using KPIs.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into total claims, total accepted claims, and total claims by month using KPIs.
           Although, by default, while calculating total sales, blank values are ignored.

![cards](https://github.com/user-attachments/assets/bf4ab37d-a278-41b0-85dc-4c5563487f22)

- Step 8 : Year and product buttons allow users to change the product and year information, filtering the data accordingly.

![button](https://github.com/user-attachments/assets/2de91b57-32b5-423a-bf39-f07b31318b83)

- Step 9 : We can view different insurance details through page icons. The highlighted icon indicates the current page.

![Page](https://github.com/user-attachments/assets/32c496b3-34fc-4866-b514-2cb2c35dc617)

  - Step 10 : The decomposition tree shows Products information based on the total claims, and it is expandable.

![Claims](https://github.com/user-attachments/assets/0023823f-fb4a-4436-bb27-33e799e65cc5)

  - Step 11 : The claim statusare shown in a lollipop chart.

![lolipe](https://github.com/user-attachments/assets/c7b4fd69-a279-49dc-bd13-d320b705ca23)

  - Step 12 : Claims by age group are shown in a spider chart.

![Spider](https://github.com/user-attachments/assets/5acc0374-a388-47e7-b249-57a52e2abbca)

  - Step 13 : Claims by ageing are shown in a bar chart.

![aging](https://github.com/user-attachments/assets/df95fbcf-1573-4aca-9742-4fd0df085d28)

- Step 14 : The report was then published to Power BI Service.
# Snapshot of Dashboard

![First](https://github.com/user-attachments/assets/b87b3aa3-f6c6-49d7-8e63-5638c89d8cd7)

![Second](https://github.com/user-attachments/assets/57f167e7-1e0e-4069-ae71-8fe9e581ebfb)
![Trid](https://github.com/user-attachments/assets/9a1f83ca-53d6-4943-a8ce-070a35670cdc)

![four](https://github.com/user-attachments/assets/7a5e660f-0402-4b86-aafa-3eb21e5fa955)

## Template 2
- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except columns.
- Step 5 : In the report view, under the view tab, theme was selected.
- Step 6 : A new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 7 : We can view different insurance details through Menu icons. The highlighted icon indicates the current page.

![Menu](https://github.com/user-attachments/assets/7f8b5b93-8272-4a52-8f54-9c37264ad6a3)

- Step 14 : The report was then published to Power BI Service.
# Snapshot of Dashboard

![First](https://github.com/user-attachments/assets/2e0d9879-beca-4f53-823e-55416f20e2b9)

![Second](https://github.com/user-attachments/assets/3458881a-f147-4937-a2c8-8b613e118a12)

![Trid](https://github.com/user-attachments/assets/68312a85-d988-4d2a-987d-3710c314bd56)

![Four](https://github.com/user-attachments/assets/b133c31f-cc73-40a5-be19-54f4fcf6cdb7)
