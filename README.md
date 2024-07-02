# Workforce Intelligence Dashboard - HR Analytics Dataset (PowerBI)

## Overview
The project utilizes Power BI Dashboard capabilities to analyze and visualize key metrics across the organization to derive key valuable insights. The dashboard visually summarizes the HR Analytics dataset including employee count, age distribution, attrition, retention, budget allocation, and other important metrics. The dashboard provides easy-to-understand visuals to aid HR and management in making informed decisions through a data-driven decision-making process.

## Dashboard
The Dashboard includes graphics ranging from simple data cards to gauges, donut charts, bar graphs, and line graphs. The dashboard also features dynamic filtering where filters can applied on the fly for the entirety of the page. For example, a tiled filter containing various departments can be individually selected for a department to filter all the graphics for that selected department.

* Data Cards:
    * Employee Count : Displays the total headcount of employees.
    * Attrition : Shows the total number of employees who have left the company.
    * Average Age : Indicates the average age in years of the employees present in the company.
    * Satisfaction : Displays the average satisfaction rating of an employee out of 5.
    * Average Retention : Indicates the average time an employee has stayed within the comapany.
    * Average Performance Rating : Shows the average percentage rating of the employees

 * Monthly Budget CAP : Gauge chart with the current month's expenditure across the organization with metrics like maximum budget, target budget, and expenditure covered.

 * Acquired Educational Talent : Donut chart displaying the diversity of talent across the company associated with their degree and background.

 * Employee Count per Age Group : Horizontal bar graph showcasing the total count of employees per each age group interval.

 * Employee Count per Salary Slab : Horizontal bar graph indicating the total count of employees in each monthly salary slab interval.

 * Job Satisfaction per Educational Field : Table displaying the total employee count based on their satisfaction rating and grouped by each educational field.

 * Gender Ratio : Single bar graph with the diversity ratio of male to female employees in the organization.

 * Attrition per Years At Company : Line chart showcasing the total count of emplpyees who have left the company pver the years.

## Dataset
The dataset [HR Analytics Dataset](./Dataset/HR_Analytics.csv) consists of over 30+ features including employee count, age group, attrition, retention, monthly income, years in company, and etc. The dataset is stored in a CSV file with over 480 rows of  unique data values included with various measures and derived columns using DAX.
