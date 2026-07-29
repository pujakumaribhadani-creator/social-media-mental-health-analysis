# Social Media Screen Time & Mental Health Analysis

## Project Overview

This project analyzes social media usage patterns and their relationship with sleep, anxiety, loneliness, life satisfaction, and overall mental well-being.

The project was completed using **Microsoft SQL Server** for data cleaning and analysis, followed by **Power BI** for interactive data visualization and dashboard development.

The cleaned dataset was first analyzed in SQL Server and then imported into Power BI to create an interactive dashboard.

---

## Project Objective

The main objectives of this project are:

- Clean and prepare the dataset for analysis.
- Identify and handle missing values.
- Create meaningful Key Performance Indicators (KPIs).
- Analyze social media usage patterns.
- Understand relationships between screen time, sleep, anxiety, and wellbeing.
- Create an interactive Power BI dashboard.
- Generate meaningful insights from the data.

---

## Dataset

**Dataset:** Social Media Screen Time & Mental Health 2026

**Total Participants:** 7,000

The dataset contains information related to:

- Age
- Gender
- Occupation
- Region
- Most Used Platform
- Daily Screen Time
- Daily Notifications
- Night-Time Social Media Usage
- Average Sleep Hours
- Anxiety Score
- Low Mood Score
- Life Satisfaction
- Loneliness
- Self-Esteem
- FOMO
- Social Comparison
- Physical Activity
- Screen Time Limits
- Digital Detox
- Mental Health Support
- Wellbeing Band

---

## Data Cleaning – SQL Server

The data was imported into **Microsoft SQL Server** and cleaned before analysis.

### NULL Value Check

NULL values were checked across important columns using the `COUNT()` function.

### Gender NULL Values

The frequency of each gender category was calculated using `COUNT()`, `GROUP BY`, and `ORDER BY`.

The most frequent category was identified as the **Mode**, and missing Gender values were replaced with the Mode using the `UPDATE` statement.

### Average Sleep Hours

Mean and Median were calculated for the `avg_sleep_hours` column.

The Mean was approximately **6.96 hours** and the Median was **7 hours**. Missing values were replaced using the Mean.

---

## Key Performance Indicators (KPIs)

| KPI | Result |
|---|---:|
| Total Participants | 7,000 |
| Total Regions | 6 |
| Average Sleep Hours | 6.96 |
| Average Anxiety Score | 11.38 |
| Average Life Satisfaction | 6 |
| Successful Digital Detox | ~1K |

---

## Business Analysis

The following analytical questions were explored:

1. Which social media platform is used the most?
2. What is the average screen time by gender?
3. Which occupation has the highest average anxiety score?
4. How does night-time social media usage relate to sleep hours?
5. Which wellbeing band has the highest life satisfaction?
6. Do users who use screen time limits have different anxiety levels?
7. Does attempting a digital detox relate to life satisfaction?
8. Which region has the highest average loneliness score?
9. Which social media platforms have the highest average daily screen time?
10. How do different demographic groups compare in terms of screen time and mental wellbeing?

---

## Key Insights

- **TikTok** is the most frequently used social media platform, followed by Instagram.
- Participants who **never use social media at night** report higher average sleep duration.
- Middle-aged participants show a comparatively higher average anxiety score.
- Most participants fall under the **Moderate Wellbeing** category.
- Anxiety levels are relatively similar across different occupations and regions.
- Facebook users show the highest average daily screen time among the analyzed platforms.
- A portion of participants are actively seeking or considering mental health support.

---

## Power BI Dashboard

The cleaned SQL Server dataset was imported into **Power BI** for visualization.

### Page 1 – Project Overview
- Project introduction
- Navigation buttons
- Access to Summary & Insights

### Page 2 – Social Media Usage Insights
- KPI cards
- Most Used Social Media Platform
- Night-Time Usage vs Average Sleep
- Average Anxiety Score by Age Group
- Wellbeing Band Distribution

### Page 3 – Mental Health & Demographic Analysis
- Screen Time & Loneliness by Age Group
- Anxiety & Sleep Hours by Region
- Anxiety Score by Occupation
- Mental Health Support Status

### Page 4 – Summary & Insights
- Project summary
- Data cleaning summary
- Key findings
- Overall conclusions

---

## Tools & Technologies

- **Microsoft SQL Server**
- **Power BI**
- **DAX**
- **SQL**
- Data Cleaning
- Data Analysis
- Data Visualization
- KPI Development
- Business Analysis

## Dashboard Preview

### Page 1 – Social Media Usage Insights

![Page 1](screen%20nd%20menatlPic1.png)

### Page 2 – Mental Health & Demographic Analysis

![Page 2](screen%20nd%20menatlPic2.png)



## Conclusion

This project demonstrates an end-to-end data analytics workflow, starting with **data cleaning and analysis in SQL Server** and continuing with **interactive visualization and dashboard development in Power BI**.

The analysis provides insights into social media usage, screen time, sleep patterns, anxiety, loneliness, and overall wellbeing.

---

## Author

**Puja Kumari**

Aspiring Data Analyst | SQL | Power BI | DAX | Advanced Excel | Data Visualization
