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

<img width="475" height="286" alt="Screenshot 2025-10-16 114858" src="https://github.com/user-attachments/assets/fc72f033-df21-4a99-a7bf-69a933bdf32b" />

<img width="244" height="81" alt="499406325-568d3d7e-9f93-4f29-addd-a233d6d405c2" src="https://github.com/user-attachments/assets/00724d91-cd69-450c-8039-a39b5432f8e0" />

## 2. Rideable Type Preference

<img width="469" height="300" alt="Screenshot 2025-10-16 114941" src="https://github.com/user-attachments/assets/b508a5f0-aefe-4020-ad41-ff8e1bb283c7" />


## 3. Ride Duration

 <img width="320" height="61" alt="499408827-4e43cbbf-60e5-4580-becf-567b72790b25" src="https://github.com/user-attachments/assets/d3f9ae43-0cdc-4653-82f2-a7edbf780660" />
 
Casual riders tend to take longer rides compared to members.
## 4. Weekly and Daily usage Patterns
Analysis of rides across the week showed that Wednesday  is the most popular day for both groups, with similar usage patterns across the week, also we can see that during the day 8am and 5pm is the busiest time for both groups.
<img width="671" height="277" alt="Screenshot 2025-10-16 115222" src="https://github.com/user-attachments/assets/454a426b-cc84-4428-8b88-67c0d06e5e4b" />
<img width="665" height="283" alt="Screenshot 2025-10-16 115211" src="https://github.com/user-attachments/assets/89895cfa-3ed1-4f65-aad6-1be4190d2780" />


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
