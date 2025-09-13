## Google Play Insights
### Project Overview

This project analyzes the Google Play Store Apps dataset using SQL and Tableau.
The goal is to extract business insights such as installs by category, app distribution, and rating performance.

## SQL Analysis

### 1.Data Cleaning (data_cleaning.sql)

Removed rows with missing ratings or installs.

Standardized Installs column by removing commas/plus signs and casting to numeric.

Ensured only valid ratings (0.0 – 5.0) are retained.

### Installs by Category (installs_by_category.sql)

*Aggregated total installs per app category.

*Ranked categories by highest installs to identify popularity trends.

### Apps per Category (apps_per_category.sql)

*Counted the number of apps available in each category.

*Highlighted categories with the highest concentration of apps.

### Average Rating by Category (avg_rating_by_category.sql)

*Computed the mean rating for each category.

*Compared performance to spot categories with consistently high or low ratings.

## Tableau Dashboard

The SQL insights were visualized in Tableau Public with 3 views:

Installs by Category 
<img width="1821" height="743" alt="image" src="https://github.com/user-attachments/assets/78778bc9-3a97-4df8-93ba-1cc3f4dd2050" />


Apps per Category 
<img width="1836" height="762" alt="image" src="https://github.com/user-attachments/assets/4aa97964-8eab-4bbb-ab98-3f3b3c1aaec3" />


Average Rating by Category 
<img width="1840" height="743" alt="image" src="https://github.com/user-attachments/assets/e287f3ed-5fdd-47a0-84a1-8f3a0ab66dd7" />


[View Interactive Dashboard on Tableau Public](https://public.tableau.com/app/profile/avantika.agarwal5632/viz/GooglePlayStoreInsights_17576047609950/Dashboard1)

### Key Insights

*Games, Family, and Tools categories dominate installs.

*Family and Lifestyle categories have a high number of apps, showing competitive saturation.

*Productivity and Education apps maintain above-average ratings compared to other categories.

### Tech Stack

*SQL (MySQL / PostgreSQL / SQLite)

*Tableau Public for dashboard creation

*VS Code + GitHub for development and version control

### About

Exploratory project to analyze Google Play Store apps data and derive actionable insights for app developers, marketers, and business strategists.
