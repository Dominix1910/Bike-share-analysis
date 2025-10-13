# Cyclistic Bike-Share Analysis
Google Data Analytics Capstone Project
By Dominik Scibor

# Executive Summary
This project analyzes usage patterns of Cyclistic bike-share users to identify key differences between casual riders and annual members.
Using Microsoft Excel and Power Query for data cleaning and analysis, I found that members tend to take shorter, more frequent rides, while casual riders take longer trips.
Based on these findings, I propose targeted marketing strategies to encourage casual riders to convert to annual memberships.

   


# Business Questions
1. How do annual members and casual riders use Cyclistic bikes differently?
2. Why would casual riders buy Cyclistic annual memberships?
3. How can Cyclistic use digital media to influence casual riders to become members?

# Goals
• Maximize the number of annual memberships.
• Understand how casual riders and annual members use Cyclistic bikes differently.
• Identify strategies to convert casual riders into annual members.


# Data Preparation

The dataset was downloaded from Divvy Trip Data (https://divvy-tripdata.s3.amazonaws.com/index.html) and stored locally as Cyclistic_Data.xlsx. This project uses data from January 2024 (202401-divvy-tripdata.csv) containing over 100,000 rows and 13 columns. Each row represents an individual ride record, including ride ID, ride type, start and end times, station names, coordinates, and rider type (casual or member).

# Data Cleaning
The dataset contained valuable information but also many missing values. To ensure accuracy, I removed all rows with missing or invalid data using Power Query Editor in Excel. Most missing data resulted from incorrect coordinates, which caused missing station names and IDs. I added new columns to calculate ride duration and day of the week, and removed irrelevant columns (e.g., station names and coordinates) for clarity.
Before:
<img width="1894" height="679" alt="499405273-30333c24-5691-494c-bd51-3b980e4fd147" src="https://github.com/user-attachments/assets/bdf78475-3ac2-495f-a299-f610ca398357" />
After:

<img width="1173" height="708" alt="499405807-36765d40-e18a-4bdd-813d-aaf81b31a816" src="https://github.com/user-attachments/assets/4f1a1205-9487-4633-990f-1c314aed177e" />


# Analysis and Findings
## 1. Rider Distribution
Members completed the majority of rides during January 2024.

 <img width="575" height="319" alt="499406066-7edce017-3636-4c01-b040-0a284dab5152" src="https://github.com/user-attachments/assets/89348ba0-cb80-4f19-a9b7-ddba7b7868ee" />

<img width="244" height="81" alt="499406325-568d3d7e-9f93-4f29-addd-a233d6d405c2" src="https://github.com/user-attachments/assets/00724d91-cd69-450c-8039-a39b5432f8e0" />

## 2. Rideable Type Preference
<img width="708" height="291" alt="499407771-091c4677-c4d2-45b8-808b-a12d2e0e0e4d" src="https://github.com/user-attachments/assets/5e1ec5e8-f076-4ee8-9ab2-ff03644c4120" />

## 3. Ride Duration

 <img width="320" height="61" alt="499408827-4e43cbbf-60e5-4580-becf-567b72790b25" src="https://github.com/user-attachments/assets/d3f9ae43-0cdc-4653-82f2-a7edbf780660" />
 
Casual riders tend to take longer rides compared to members.
## 4. Weekly Usage Patterns
Analysis of rides across the week showed that Tuesday is the most popular day for both groups, with similar usage patterns across the week.
<img width="839" height="335" alt="499409766-71191544-4d7f-4cf5-9ed4-f0c77f5f9515" src="https://github.com/user-attachments/assets/f1efe62d-080c-4256-ab5c-c98ec810b782" />

# Insights and Recommendations
1. Usage Differences:
   - Members ride more frequently and take shorter trips.
   - Casual riders take longer trips but ride less often.

2. Membership Incentives:
   - Casual riders could save money by purchasing memberships, especially for longer rides.
   - Promotions highlighting cost savings could attract casual riders.

3. Digital Marketing Strategies:
   - Display post-ride summaries showing how much users could have saved with a membership.
   - Use in-app messages and station posters to promote membership discounts for frequent riders.


# Tools and Skills Use
• Tools: Microsoft Excel, Power Query, Pivot Tables, Charts
• Skills: Data cleaning, descriptive analysis, data visualization, business insights, stakeholder communication

# Next Steps
• Analyze data for multiple months to identify seasonal trends.
• Incorporate weather data or location analysis to better understand ride behavior.
• Build an interactive Excel or Power BI dashboard to visualize trends and insights.

# Conclusion
This project demonstrates my ability to clean, analyze, and visualize real-world datasets to generate actionable insights. It highlights how data-driven recommendations can support business goals, such as increasing Cyclistic memberships through targeted digital engagement.
