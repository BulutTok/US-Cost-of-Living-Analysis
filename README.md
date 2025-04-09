# US-Cost-of-Living-Analysis

Below is the final plain text version of your README file with code that “places” (embeds) your image files. Make sure you create an “images” folder in your repository and move the following image files there:

• Statewise_Wealth.png  
• All_States_Dasboard.png  
• Average_Cost_of_Living_Map_Across_the_U.S..png  
• Statewise_Average_Living_Cost.png

Once placed in the “images” folder, GitHub will render the images when viewing the README.

------------------------------------------------------------
US COST OF LIVING ANALYSIS

Overview:
This repository contains a comprehensive analysis titled “A Comprehensive Analysis of the Cost of Living in the United States (2020).” As part of the MIS 505 Data Visualization final project at the University of North Carolina, Wilmington, this project examines various cost-of-living metrics across U.S. states using 2020 data. The analysis focuses on household expenditure trends, income dynamics, and regional disparities, and includes interactive visualizations created with Tableau.

Table of Contents:
1. Overview  
2. About the Data  
3. Data Preprocessing  
4. Visualizations and Analysis  
5. Results  
6. Files Included  
7. How to Run / View the Project  
8. Course Context  
9. Contact  

1. Overview:
This project investigates U.S. cost-of-living metrics from 2020. It explores key cost categories—housing, food, transportation, healthcare, childcare, other necessities, and taxes—as well as overall household expenditures and median family incomes. Detailed insights and visual comparisons help illustrate the financial landscape across states.

2. About the Data:
The primary dataset, “Cost of Living in the United States (2020),” includes:
• A unique case identifier (case_id)  
• State name (state) and other location details (areaname, county)  
• Household attributes (family_member_count)  
• Expense-related columns for housing, food, transportation, healthcare, childcare, other necessities, and taxes  
• The total aggregated cost (total_cost)  
• The median family income (median_family_income)  

Each row represents a unique case, providing the basis for a detailed analysis of household expenses and income levels.

3. Data Preprocessing:
The original dataset was provided in a wide format, with separate columns for each cost category. Using Python and the Pandas library, the data was reshaped into a long format by “melting” the individual cost columns into two unified columns: “Cost Type” and “Cost Value.” This reshaped dataset, saved as “cost_of_living_us(Reshaped).csv,” ensures consistency and streamlines analysis in Tableau.

4. Visualizations and Analysis:
The project features a range of interactive visualizations that examine:
• Total Annual Household Expenditure – A bar chart depicting overall U.S. household spending.  
• Distribution of Household Spendings – Dual-bar charts breaking down cost-category contributions.  
• Statewise Expenditure Analysis – Treemaps and maps illustrating expenditure differences across states.  
• Average Living Cost Analysis – Comparisons of average cost-of-living metrics by state.  
• Income Dynamics – Visualizations highlighting average annual household incomes and income diversity.  
• Wealth and Cost Disparities – Comparative analyses of income surpluses and deficits by state.  
Each visualization provides both a visual critique and data-driven interpretation to reveal trends and regional financial disparities.

5. Results:
Below are selected screenshots from the project with detailed interpretations. The image files are embedded into this section using HTML code. (Ensure these files are placed in the “images” folder.)

------------------------------------------------------------
RESULTS

a. Statewise Wealth Visualization  
------------------------------------------------------------
Image File: Statewise_Wealth.png  
------------------------------------------------------------
<img src="images/Statewise_Wealth.png" alt="Statewise Wealth Visualization" />

Interpretation:
• This visualization illustrates the state-by-state differences between median family income and total living cost, highlighting where income exceeds expenses (surplus) or falls short (deficit).  
• For example, states like Rhode Island show a strong income surplus, whereas states such as West Virginia exhibit a significant income deficit.  
• Color coding and annotations enhance quick identification of regional economic disparities.

------------------------------------------------------------
b. All States Dashboard  
------------------------------------------------------------
Image File: All_States_Dasboard.png  
------------------------------------------------------------
<img src="images/All_States_Dasboard.png" alt="All States Dashboard" />

Interpretation:
• This comprehensive dashboard aggregates multiple cost-of-living metrics and household expenditure data for all states.  
• It provides an at-a-glance comparison of overall spending, enabling identification of states with notably high expenditures (such as Texas) versus those with lower spending (like the District of Columbia).  
• The dashboard serves as a starting point for deeper exploration of regional economic patterns.

------------------------------------------------------------
c. Average Cost of Living Map Across the U.S.  
------------------------------------------------------------
Image File: Average_Cost_of_Living_Map_Across_the_U.S..png  
------------------------------------------------------------
<img src="images/Average_Cost_of_Living_Map_Across_the_U.S..png" alt="Average Cost of Living Map Across the U.S." />

Interpretation:
• This color-coded map depicts the average cost of living by state using a gradient scale where darker hues indicate higher costs.  
• It clearly distinguishes high-cost regions (e.g., Washington, D.C.) from more affordable areas (e.g., Mississippi).  
• The geographic visualization helps illustrate regional disparities in living costs across the country.

------------------------------------------------------------
d. Statewise Average Living Cost  
------------------------------------------------------------
Image File: Statewise_Average_Living_Cost.png  
------------------------------------------------------------
<img src="images/Statewise_Average_Living_Cost.png" alt="Statewise Average Living Cost" />

Interpretation:
• This chart provides detailed average living cost information for each state, ranking them from most expensive to most affordable.  
• It reveals the range of living expenses, allowing for easy identification of states with particularly high or low costs.  
• Such detailed insights are critical for understanding the financial pressures at the state level and for comparing regional cost differences.

------------------------------------------------------------

6. Files Included:
• cost_of_living_us.csv – The original wide-format dataset.  
• cost_of_living_us(Reshaped).csv – The reshaped dataset for analysis.  
• Data Visualization-Final Project Cost of Living.twbx – The Tableau workbook with interactive visualizations.  
• Module 7- Data Visualizations Final Project.pdf – Detailed project documentation and design evaluation.

7. How to Run / View the Project:
To explore the interactive visualizations:
a. Download and install Tableau Desktop or Tableau Public from https://www.tableau.com/.  
b. Open the “Data Visualization-Final Project Cost of Living.twbx” file.  
c. Use the interactive filters, tooltips, and actions to delve into various insights.  
For data review or to re-run preprocessing, refer to the provided CSV files.

8. Course Context:
This project was developed for the MIS 505 Data Visualization course at the University of North Carolina, Wilmington. It demonstrates practical applications of data preprocessing, visualization design, and analytical evaluation to reveal economic trends and household cost disparities across the United States.

9. Contact:
For any questions or feedback regarding the project, please contact:
Bulut Tok  
Email: bt6631@uncw.edu
