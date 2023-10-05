# Power BI Dashboard for Data Professionals
![]()
## Overview
This documentation provides a detailed account of the data cleaning and visualization process for the project, starting from data preparation to the creation of visualizations. The project aimed to analyze survey data collected from data professionals and gain insights into various key performance indicators (KPIs).

### Data Cleaning
1. **Date Column Removal:** The date column was removed due to errors and inconsistencies.

2. **Empty Column Removal:** Four empty columns were identified and subsequently removed.

3. **Salary Column Transformation:** The salary column contained salary ranges with attached strings. To clean this data:
    - The column was split into digits and strings.
    - The string characters were removed.
    - A new calculated column was created to compute the average salary range.

4. **Column Splitting:** Columns like job title, country, and education contained multiple options separated by special characters. These columns were split to extract individual options.

### Data Visualization
After cleaning and preparing the data using Power Query, the visualization phase commenced to analyze various KPIs:

1. **Average Age of Survey Respondents:**
   - Visualization: A visual card.
   - Purpose: Providing insights into the demographic composition of survey participants.

2. **Total Number of Survey Respondents:**
   - Visualization: A visual card.
   - Purpose: Offering an overview of the survey's reach and participation.

3. **Average Salary by Job Title:**
   - Visualization: A stacked bar chart.
   - Purpose: Analyzing the income distribution among respondents based on their job roles.

4. **Country of Survey Participants:**
   - Visualization: A Treemap.
   - Purpose: Identifying the geographical distribution of survey respondents.

5. **Preferred Programming Language:**
   - Visualization: A stacked column chart.
   - Purpose: Highlighting the programming languages favored by respondents.

6. **Perceived Difficulty in Entering the Data Field:**
   - Visualization: A donut chart.
   - Purpose: Assessing the perceived challenges faced by individuals attempting to enter the data profession.

7. **Satisfaction with Salary:**
   - Visualization: A gauge chart.
   - Purpose: Gauging the level of contentment among respondents regarding their earnings.

8. **Work/Life Balance Satisfaction:**
   - Visualization: A gauge chart.
   - Purpose: Measuring respondents' satisfaction with their work-life balance.

## Conclusion
This documentation outlines the data cleaning and visualization processes undertaken for this project. The resulting visualizations provide valuable insights into the survey data, enabling data-driven decision-making and a deeper understanding of the data professional landscape. The cleaned data and visualizations are available in the project repository for further analysis and exploration.
