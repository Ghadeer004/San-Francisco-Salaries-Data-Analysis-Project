Overview
This project performs a comprehensive data analysis of the San Francisco Salaries dataset (covering the years 2011–2013). Using Python and the Pandas library, the analysis explores compensation patterns, identifies top earners, calculates the impact of various pay components, and visualizes the city's salary budget distribution.

Features & Analysis Tasks
The analysis is divided into four main sections:

Filtering & Sorting:

Identified the employee with the highest Overtime Pay in 2013.

Retrieved the top 5 employees with the highest Base Pay in 2011.

Calculated Fields:

Created a Total Pay metric (Base + Overtime + Other Pay).

Calculated the percentage of Other Pay relative to total compensation to identify "high-bonus" earners (e.g., employees earning >50% of their salary from "Other Pay").

Categorical Analysis:

Used string processing to categorize all "Curator" related job titles.

Calculated the headcount and average base pay for Curators during 2012-2013.

Data Visualization Dashboard:

Top 5 Jobs by Total Pay: A bar chart showing the highest aggregate compensation by title.

Top 5 Jobs by Overtime Pay: A bar chart highlighting roles with the highest overtime costs.

Budget Breakdown: A pie chart illustrating the percentage distribution between Base, Overtime, and Other Pay.

Technologies Used
Language: Python 3

Libraries: * Pandas: Data manipulation and cleaning.

Matplotlib & Seaborn: Data visualization and dashboarding.

Environment: Jupyter Notebook / Google Colab

Dataset
The analysis is based on the Course_Project_SanfranSicso_Salaries (1).xlsx file, which includes detailed records of employee names, job titles, and various pay types.

Visualizations
The project includes an interactive dashboard generated via Seaborn and Matplotlib:

Viridis Palette: Used for Total Pay analysis.

Magma Palette: Used for Overtime Pay analysis.

Pie Chart: Exploded view for the salary budget contribution.
