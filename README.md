# Sports Analytics: Cricket Data Insights

Overview

This analysis focuses on the T20 Cricket World Cup 2022, where England secured the championship against Pakistan. The project highlights practical approaches to examining cricket match data and player performance.

<img src='https://github.com/1adityakadam/Sports_Analytics_Cricket_Data_Insights/blob/main/GIF%20Files/project1.gif' >


## Main Components

- Strategic Team Selection: The analysis aimed to build a balanced squad able to score 180 runs regularly while defending targets of 150 runs. This involved integrating practical strategy with data-driven evaluation.

- Data Collection:
  Match data was gathered directly from ESPNcricinfo:  
  "https://www.espncricinfo.com/series/icc-men-s-t20-world-cup-2022-23-1298134/match-schedule-fixtures-and-results"  
  Using BrightData, the raw webpage content was converted into a structured JSON format:
  
- Preparation: The raw JSON data was organized into tables. Data cleaning and preprocessing were performed with Pandas to ensure accuracy and consistency:

- Power BI was used to visualize the CSV data. Power Query helped further refine the data, and relationships were formed using team and match IDs. DAX formulas supported calculations, sorting, and data typing.

- Defining Player Roles: Each position—openers, power hitters, middle-order, finishers, all-rounders, and fast bowlers—was clearly classified using metrics such as average, strike rate, and ability to score boundaries.

## Interactive Dashboard Highlights

- Openers and Power Hitters: Explore batting statistics and historical performances with interactive features. Hovering over any player's row reveals detailed metrics.

- Middle Order Analysis: Review middle-order batsmen's performances and match histories with personalized insights.

- Middle Finisher Insights: Analyze the metrics for lower-order batsmen focusing on their finishing abilities.

- All Rounders Overview: Assess the all-round players for both batting and bowling contributions. 

- Fast Bowlers Focus: Visualize the impact of specialist fast bowlers on match outcomes.

- Team Selection: Select the final eleven players with a summary of their batting and bowling achievements.

- BI dashboards developed for this project present clear, interactive visualizations that enable deep insights into T20 cricket team composition and player performance.
