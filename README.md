# Uncovering causes of Flight Delays: An Airline Operations Analysis
## 🌐 [PORTFOLIO](https://lamidikhadijat.vercel.app/) 🔗[LinkedIn](https://www.linkedin.com/in/khadijatlamidi/) 👀 READ FULL ARTICLE ON MEDIUM

# 🌼Project Overview

# Objective

# 🧰 Tool
| Tool | Purpose|
|------|--------| 
| Microsoft Excel | Cleaning and Visualization |
|Power Query| Transformation |
|Power Pivot| Data Modeling to ensure interactivity

# Data Description
 The datasets were obtained from Kaggle. It follows a star schema model with one fact table and 3 dimensional table.
 
| Tables | Description | Rows |
|--------| ------------| -----|
| fact_flights |Contains information about individual flights |1,048,575 |
|dim_airport_origin|contains information about the airports included in the dataset. | 322|
|dim_airport_destination| contains information about the airports included in the dataset.|322 |
|dim_airline| contains information about the different airlines operating in the country.| 14 |
|dim_date| contains calendar information used for time intelligence calculations| 69|
|delay reason| aderived table created from the Flight table to facilitate the analysis of recorded flight delay reasons | |

# Data WorkFlow
Data Collection
      ↓
Data Cleaning
      ↓
Data Modeling
      ↓
Data Analysis
      ↓
Dashboard Development
      ↓
Insights & Recommendations

1. Data Collection: The dataset was obtained from Kaggle.
2. Data Cleaning: Ensure data quality and Checked for duplicates
3. Data Transformation: created new columns to help with the analysis
4. Data Modeling: Created relationships between tables and designed a star schema for reporting.
5. Data Analysis: Created Pivot Tables and DAX measures 
6. Dashboard Development: Built an interactive dashboard in Excel to visualize key metrics.
7. Reporting: Documented key findings and provided actionable recommendations.

# Data Model
<img width="738" height="366" alt="Image" src="https://github.com/user-attachments/assets/a354509b-b6c7-4ffe-ab13-142ccf795bb8" />

# 📌 Key Insights
- Flight Delay Analysis
- <img width="645" height="420" alt="Image" src="https://github.com/user-attachments/assets/1a31f20b-81e1-48fd-86b3-35630661fea1" />

## Insights
a. The overall flight performance showed a mixed pattern. Over the months the total flights and delayed flights decreased but the average delay duration increased. This suggests that fewer flights didn't necessarily mean shorter delays.
b. March recorded fewer delayed and cancelled flights. Although, comparing its total counts with those of the complete months of January and February would be misleading.
c.  The most frequent delay reason was not necessarily the reason associated with the longest average delay. Although weather delays occurred less frequently, they had the highest average duration, showing the importance of examining both delay frequency and duration.
d.  ORD airport had the highest delay count, making it an important airport for further investigation. However, this does not automatically mean it had the poorest punctuality performance because airports handle different numbers of flights.
e. Approximately 55% of United Airlines flights in the dataset were delayed. This indicates a potential punctuality concern that may warrant further investigation.

# Recommendations
|Priority| Recommendation| Impact | Suggested Owner|
|--------|---------------|-----------------|----------------|
|High | Investigate the factors contributing to United Airlines’ high delay rate of approximately 55% | Identify potential operational issues and opportunities to improve punctuality| United Airlines Operations Management|
|High| Investigate why weather delays have the highest average delay duration of 44.9 minutes | Identify opportunities to improve disruption preparedness and reduce the impact of weather-related delays| Airline Operations and Airport Operations Teams
| Medium | Investigate the high number of delayed flights recorded at Chicago O’Hare International Airport (ORD)| Identify potential congestion or operational bottlenecks that may contribute to delays | Airport Operations Management |
|Medium | Examine the most frequently recorded delay reason | Better understand the most common recorded delay category and identify areas for further investigation | Airline Operations Teams and Relevant Air Traffic Management Authorities|
|Low | Extend the analysis to cover a longer period, ideally a full year | Data Analysis Team|

# Limitations
 - The dataset covers 1st January to 10th  March 2015, meaning March contains incomplete records and cannot be directly compared with the two full months. The limited time coverage restricts the ability to identify long term trends and seasonal patterns in flight performance.
- The dataset includes recorded delay reasons, it does not provide sufficient information to establish the underlying operational factors responsible for each delay.

# Author
Lamidi Khadijat - Data Analyst

# 🔗 Connect With Me
-  [LinkedIn](https://www.linkedin.com/in/khadijatlamidi/)
- [Portfolio](https://lamidikhadijat.vercel.app/)
- [Email](mailto:omowunmikhadijat011@gmail.com)
- [Medium](https://medium.com/@omowunmikhadijat011)


  
