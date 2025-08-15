# PowerBI-HR_Dashboard

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiMWU0YmM4YjUtNTY4OC00MGI5LWIzMGYtZDk0ZmNkNWFhNDBkIiwidCI6IjhhOGY0OGUyLTdmOTktNDU5OC05MTAwLWEwZjBjY2M0Yjg5NiIsImMiOjZ9

The PowerBI HR Dashboard analyzes employee work preferences (work-from-home vs. office) and wellness trends from April to June 2022. It provides a single-page, interactive visualization of presence, work-from-home, and sick leave percentages, segmented by employee, day of the week, and month. Built using PowerBI Desktop and published to PowerBI Service, it leverages DAX measures and data transformations to deliver actionable insights for optimizing office planning and employee engagement.

## Objective

The PowerBI HR Dashboard aims to provide actionable insights into employee work preferences and wellness trends to optimize hybrid work strategies. It tracks work-from-home and office attendance patterns, identifies high sick leave periods, and supports data-driven decisions for scheduling team activities, managing office space, and reducing infrastructure costs.

### Steps followed 

- Step 1 : Load and transform Excel data by merging multiple sheets with different column headers (representing dates) into a single column. Ensure the process avoids hard coding, allowing it to be applicable to additional sheets.
- Step 2 : Add extra columns (work from home count, month, sick leave count, day of week) to the transformed data, alongside measures using DAX (present %, present days, sick leave %, sick leave count, total working days, work from home %, work from home count). The measures are organized together in a separate measures table.
- Step 3 : Display presence %, work from home %, and sick leave % on the dashboard, segmented by employee, day of the week, and overall trend by date. Additionally, break down the data by each month.

## Insights

A single page report was created on Power BI Desktop and it was then published to Power BI Service provided in the above link. 

### Apr 2022 - Jun 2022

#### Presence
- 91.83%
- Decreasing trend
- Most present on Monday and least present on Friday

#### Work From Home
- 10.00%
- Trending with little variation
- Work from home highest on Friday and lowest on Tuesday

#### Sick Leave
- 1.10%
- Increasing trend
- Highest sick leave on Monday and lowest on Friday

## Acknowledgments

- [Dhaval Patel](https://www.youtube.com/@codebasics)




