# HR Analytics Dashboard

### Dashboard Link: https://app.powerbi.com/view?r=eyJrIjoiYTE2OWEwZGItYTQzMi00NzU0LWEzZjUtYTAyZGUyZTlmMWI5IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9

## Problem Statement
The Executive Dashboard provides a clear and comprehensive summary of key workforce metrics such as headcount, diversity, hiring, salary, and attrition. You can access detailed information by clicking on specific metrics like Headcount, Hires, or Terminations.
This dashboard is designed for ease of use, enabling quick and efficient analysis of all important KPIs within a unified view.
The report is based on ideas from the Agile Insights website and utilizes self-created and dummy data. Its primary purpose is to demonstrate the functionality and visualization capabilities of the dashboard. Please be aware that the data presented may not be accurate.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except columns.
- Step 5 : In the report view, under the view tab, theme was selected.
- Step 6 : A new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 7 : One card visual was added to the canvas, representing Head count, % female Leader, total screening, total salary and attrition. 
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into Head count, % female Leader, total screening, total salary and attrition.
           Although, by default, while calculating total sales, blank values are ignored.

![Cards](https://github.com/user-attachments/assets/2907d65b-0ebe-465f-ab79-79a7512f4fbc)

- Step 8 : Users can filter data using the slicer.

![Slicer](https://github.com/user-attachments/assets/4f3c1dc6-8d00-49d2-a613-9edec66ca000)

- Step 9 : Below, I’ve included a screenshot of these icons. By clicking on an icon, users can navigate to a specific page and view the details.

![Icons](https://github.com/user-attachments/assets/57df1102-6ea4-4379-a3d2-b989eb5064de)
        
- Step 10 : The Self-Serve Report is a new feature. By clicking on the Self-Serve Report icon, you can navigate to the Self-Serve Report page, where you can ask questions.

![Self report](https://github.com/user-attachments/assets/5022af7b-44bd-4aef-a064-a43c8f3d085e)

- Step 11 : : Below, I’ve included a screenshot of these icons. By clicking on an icon, users can navigate to a Home page.

![Home icon](https://github.com/user-attachments/assets/64fa7379-e93f-42d2-8f30-0224723e199b)

- Step 12 : The report was then published to Power BI Service.
 
# Snapshot of Dashboard 

![Main page](https://github.com/user-attachments/assets/c33f94fe-7e40-415a-a82a-a3a90cf6f444)

- Step 13 : I’ve included a screenshot below. By right-clicking on the graph, you can drill through to the details page.


![drill through](https://github.com/user-attachments/assets/aa28b590-683e-4b96-8339-7f630c80d2db)


# Employee Profile
This dashboard displays personal information for each employee.

![Employee profile](https://github.com/user-attachments/assets/8522d871-1354-45b6-b0c8-1c6533a915b2)

Here’s a new feature: when users hover over employee details, they can see the employee's photo.

![Personational inf](https://github.com/user-attachments/assets/27aa38be-b42f-48aa-aa3d-3d3f9c0a4240)

#  Diversity
With a dynamic dashboard at their disposal, HR specialists can explore demographic data and focus on specific factors such as gender. This dashboard highlights various metrics related to the company’s diversity, including the proportion of women in senior positions and the distribution of employees across different age groups.

![Diversity](https://github.com/user-attachments/assets/16abfeb6-c797-43a7-b78e-904036e2a734)


# Hiring
Enhancing Your Talent Acquisition Strategy. This dashboard offers a detailed overview of the recruitment process. Obtain clear insights into key performance indicators and resume screening. Customize your analysis using filters for timeframes, organizational units, and locations.

![Hiring](https://github.com/user-attachments/assets/0dd0fdfc-366b-471d-8db8-1d5b6963c25c)

# Salary Analysis
This dashboard provides an analysis of average salaries across different categories, such as organization, time periods, gender, age groups, and geographic regions.

![Salary Analysis](https://github.com/user-attachments/assets/ae30ac89-baf0-49e5-ac78-1abd2ad4786e)


# Attrition Analysis
Insights to Reduce Turnover and Enhance Retention
Understanding employee turnover is vital for evaluating satisfaction and uncovering factors that contribute to attrition. This dashboard provides a detailed breakdown of turnover rates, differentiating between voluntary and involuntary exits, and offers insights segmented by tenure, seniority, gender, and age.

![Attrtion Analysis](https://github.com/user-attachments/assets/279e306a-d360-44cb-970d-8d513a8937cf)

# Self-Serve Report
Users can input their questions in the Ask Data section. The suggestions displayed in the data cards can guide you in exploring the data further. To see all available suggestions, click "Show All Suggestions." To define the type of visualization, use the keyword "as." For example, you might write, "Show headcount by organization level as a column chart.”

![Self Serve report](https://github.com/user-attachments/assets/81c31b18-7d3f-4d5a-b095-34b665f741cc)

