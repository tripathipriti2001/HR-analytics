# [HR Analytics Dashboard using Power BI 🔗](https://drive.google.com/file/d/1h30yQ-tukzdef7TLYNqnkKJKS_5BZZmr/view?usp=sharing)

## Objective

The objective of this project is to identify the key factors driving employee attrition and provide actionable insights for improving workforce retention in an organization.
This dashboard provides insights of the attrition of an organization which helps the HR team for their further analysis.

Throughout this project, I've had the chance to:

- Dive deep into HR data to uncover valuable insights.
- Develop interactive dashboards to visualize key HR metrics.
- Provide data-driven recommendations for strategic decision-making.

## Steps followed:

Firstly, Download the dataset.

**1. Data Gathering:** 
  - Importing raw data .csv file into Power BI & transform to Power Query editor for cleaning and data processing.
          
**2. Data cleaning:**
  - Cleaning is done by removing empty column, removing duplicates, errors etc.
  - Replacing values in column with proper values and naming.
  - Detecting data type of every column, using the auto detect data type function in Power query editor.
          
**3. Data processing:**
  - In the Power Query editor, creating new column called "AttritionCount" by using conditional column feature in add column which is created on the basis of certain condition like (IF attrition = 'Yes' then 1, Else 0).
  - This new column is further used for creating different KPI's and charts.Then creating the Attrition Rate by applying DAX queries, adding new measure (Attrition Rate = SUM([AttritionCount]))/SUM([Employeecount])) in %.
          
**4. Data analysis:**
  - Analysis involves the creation of a range of visual representations, including bar charts, key performance indicators (KPIs), table charts, pie charts, and other relevant visualizations.
  - These tools are utilized to gain insights and present data in a comprehensive and easily understandable manner.

[ Dashboard](https://drive.google.com/file/d/1h30yQ-tukzdef7TLYNqnkKJKS_5BZZmr/view?usp=sharing)


   
