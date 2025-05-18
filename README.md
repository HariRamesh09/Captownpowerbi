# Power BI Project: Student Survey Analysis

## Project Overview
This project involves analyzing a dataset from a student survey conducted in various stores across the United States. The survey captures the spending habits of students on different types of purchases such as video games, indoor games, toys, books, gadgets, etc. The dataset includes information about the store location and store setting.

## Objectives
The main objectives of this project are:
1. To extract meaningful insights from the student survey dataset.
2. To create various visualizations to represent the data effectively.
3. To implement data access restrictions for specific users.
4. To publish the report on Power BI cloud service and design a master dashboard.
5. To use the Q&A feature of Power BI for additional insights.

## Visualizations Created
1. **Tabular Visualization**: Format the total amount of purchase (TAP) based on 'Store location' and 'Store setting':
   - If 0 < TAP < 35000, then records should be in red color.
   - If 35000 <= TAP < 60000, then records should be in yellow color.
   - If TAP >= 60000, then records should be in blue color.

2. **Matrix Visualization**: Create a matrix visualization to show the amount spent on outdoor sports across different ages and 'Store setting'. Apply color formatting for the total amount spent on outdoor sports.

3. **Funnel Chart**: Create a funnel chart to show the total amount of purchase by 'Store setting'. Display the data labels as a percentage of the first value.

4. **Pie Chart**: Show the total amount of purchase by different 'Store location' for suburban 'Store setting' only. Use filter context to achieve this.

5. **Scatter Plot**: 
   - Show video games purchase and outdoor sports spent across different ages.
   - **Sand Dance Plot**: Show indoor sports and video games spent across different age groups.

6. **Data Access Restrictions**: Restrict data access for users based on the 'User mapping' table. For example, a user dealing with rural areas should only view data related to rural areas.

## Publishing Instructions
1. Publish the report on Power BI cloud service.
2. Design the master dashboard consisting of the funnel chart and scatter plots.
3. Create a schedule refresh for six times every 4 hours for the dashboard in a day.

## Q&A Feature Usage
1. Use the Q&A feature to show the average age of students.
2. Create a donut chart for the total amount of purchases by 'Store location'.
