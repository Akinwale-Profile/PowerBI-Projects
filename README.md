
## Customer Churn Analysis and Retention Strategy for Thundra

![Screenshot (185)](https://github.com/user-attachments/assets/def07ffe-a8e6-40b0-bb39-af0d22b9452d)



## Problem Statement
Customer churn poses a significant challenge to businesses, directly impacting revenue and growth. Identifying the factors contributing to customer attrition and predicting potential churners are critical for implementing targeted retention strategies. However, the absence of a robust analytical framework often leads to inefficient decision-making and poor customer relationship management.

## Project Overview
This project addresses the issue of customer churn through a comprehensive data analysis and predictive modeling pipeline. Using SQL, Power BI, and Python, the project delivers actionable insights and predictive capabilities to mitigate customer churn effectively. The project workflow integrates data cleaning, exploration, visualization, and machine learning to offer a holistic solution.

## Key Steps and Solutions
Data Preparation in SQL:

Created a structured database for customer data, ensuring quality through null checks and cleaning.
Conducted exploratory SQL queries to analyze key attributes like gender, contract type, and state distribution.
Aggregated revenue metrics and identified null values for corrective actions.
Data Transformation for Reporting:

Designed Power Query transformations in Power BI to enrich the dataset, including calculated columns for churn status, age groups, and tenure segmentation.
Mapped categorical variables to enable better grouping and visualization of data.
Insightful Visualizations:

Built interactive Power BI dashboards to track metrics such as churn rate, customer demographics, and revenue breakdowns.
Highlighted critical insights, including high-risk customer segments and revenue contributions by churned customers.
Predictive Modeling in Python:

Implemented a Random Forest classifier to predict potential churners based on historical data.
Conducted feature importance analysis to identify the most influential factors driving churn.
Developed a pipeline for making predictions on new customer data, enabling proactive retention strategies.

![Screenshot (184)](https://github.com/user-attachments/assets/7dcfc4f6-8443-40f8-9c52-1e3216367fae)


## Business Impact:

- Empowered stakeholders with insights into churn drivers and customer behavior.
- Enabled targeted retention campaigns by identifying customers at risk of churn.
- Enhanced decision-making capabilities through predictive analytics and interactive reporting.

This project exemplifies a data-driven approach to solving customer churn challenges, leveraging advanced analytics and machine learning for impactful business outcomes.



# Exploring trends and insights among data professionals

![Screenshot (178)](https://github.com/user-attachments/assets/779e3f5c-ad9f-4b58-b362-109c440cb2ce)

## Problem statement

Organizations require an efficient way to analyze survey results from data professionals, focusing on trends, preferences, and challenges in the industry. The lack of a clear visualization system to communicate these insights limits decision-making capabilities.

## Steps taken for analysis
Data Preparation:

- Imported survey data containing responses from professionals in the data industry.

- Cleaned and transformed the dataset to ensure consistency and accuracy.

- Established relationships between key entities like demographics, preferences, and performance metrics.

## Exploratory data analysis:

- Identified key metrics, such as average satisfaction levels and top challenges faced by data professionals.

- Used descriptive statistics to uncover initial trends.

## Data modeling:

- Created a relational model using primary and foreign keys for seamless integration.
- Designed a scalable structure to allow dynamic filtering and slicing.

## Report Design:

Configured multiple visualizations, including bar charts, line graphs, and KPI indicators, to represent survey insights effectively.

Focused on usability, with interactive filters for demographic segmentation and time-based trends.



![Screenshot (188)](https://github.com/user-attachments/assets/d31703c3-1761-4dab-9e5f-24bc84c748f6)

## Problem Statement

The Midwestern United States is home to numerous industrial facilities that play a critical role in sustainability efforts, including waste management, recycling, and energy recovery. Despite significant progress in some areas, the region faces challenges such as:

- Uneven adoption of sustainability practices across states.
- Disparities in waste production and recycling efforts among facilities.
- Underutilized opportunities for energy recovery.
- Lack of actionable insights for prioritizing improvement efforts.

This report aims to analyze sustainability metrics for facilities in Midwestern states to identify leaders and laggards, uncover inefficiencies, and provide actionable recommendations to enhance sustainability performance.

## Essence of the Report
This analysis focuses on:

- Highlighting Key Metrics: Examining waste production, recycling efforts, and energy recovery across facilities.
- Driving Data-Driven Decisions: Providing insights to help stakeholders target underperforming facilities and regions.
- Promoting Sustainability: Supporting efforts to achieve waste reduction and improved recycling rates while optimizing energy recovery.
- The report combines dynamic visualizations and interactivity to enable stakeholders to filter data by state, year, and facility name, offering a comprehensive view of sustainability performance.

## Data Cleaning Process
The raw dataset contained a wealth of information but also presented challenges such as irrelevant columns, mixed data types, and missing values. The data cleaning was conducted in Python using the pandas library, which provided robust tools for handling and transforming the dataset. Below are the steps taken to prepare the data for analysis in Power BI:

## Selection of Relevant Columns:

Focused on key sustainability metrics: waste production, recycling (on-site and off-site), energy recovery (on-site and off-site), and production ratios.
Included geographical fields like state, county, and city for regional analysis.
Renaming Columns:

Simplified column names to make them easier to interpret in Power BI (e.g., renaming 113. 8.2 - ENERGY RECOVER ON to Energy Recovery On-Site).

## Data Type Conversion:

Converted numeric fields like Energy Recovery On-Site and Total Waste Production to appropriate data types to ensure accurate calculations.
Handling Missing Values:

Dropped rows with missing critical fields such as State and Total Waste Production to maintain data integrity.
Filtering for Midwest States:

Focused the dataset on Midwestern states, including Illinois, Indiana, Iowa, Kansas, Michigan, Minnesota, Missouri, Nebraska, North Dakota, Ohio, South Dakota, and Wisconsin.
Saving the Cleaned Dataset:

Exported the cleaned dataset as a CSV file for seamless import into Power BI.
Analysis and Visualization
The report’s visualizations address the following key analyses:

## Uneven Sustainability Performance Across States:

Maps and bar charts highlight variations in waste production, recycling, and energy recovery across Midwestern states.
Facilities with High Waste Production:

Tree maps and tables identify facilities contributing the most to waste, providing targets for waste reduction initiatives.
Inconsistent Recycling Efforts:

Clustered bar charts compare on-site and off-site recycling rates by facility, revealing disparities and potential areas for improvement.
Ineffective Energy Recovery:

Scatter plots visualize the relationship between waste production and energy recovery, pinpointing underperforming facilities.

## Conclusion
This report provides a comprehensive overview of sustainability performance in the Midwest. It equips stakeholders with actionable insights to drive improvements in waste management, recycling, and energy recovery. By identifying key areas of inefficiency and disparity, the report supports informed decision-making and fosters progress toward a more sustainable industrial ecosystem.
