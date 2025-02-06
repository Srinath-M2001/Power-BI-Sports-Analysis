# Olympic Data Analysis Dashboard

## Objectives
The primary objective of this project is to leverage Olympic data to create a dynamic dashboard using Power BI, enabling stakeholders to explore trends, insights, and patterns related to the Olympic Games. This project incorporates data analysis and visualization to answer key questions about the history, participants, events, and outcomes of the Olympics.

## Significance
The Olympics represent a global celebration of sports and culture. Analyzing the vast dataset of the Olympic Games offers several benefits:

1. **Understanding Trends**: Identify patterns in the hosting of games, popularity of sports, and changes in participation over time.
2. **Performance Insights**: Analyze the performance of countries, regions, and participants across various sports and events.
3. **Data-Driven Decision Making**: Provide actionable insights for policymakers, sports organizations, and researchers.
4. **Historical Context**: Explore the evolution of the Olympics, including emerging sports and changes in event structures.
5. **Interactive Exploration**: Allow stakeholders to interact with the data dynamically, providing tailored insights based on specific interests.

---

## Data Structure
The analysis is based on the following 11 tables, structured as shown in the ER diagram (refer to the image):

### Tables and Relationships
1. **City**: Contains city names and identifiers.
2. **Competitor Events**: Tracks participants, events, and medal data.
3. **Event**: Contains event details, including gender categories.
4. **Games**: Includes information about Olympic editions (year, season, etc.).
5. **Games City**: Links games with hosting cities.
6. **Games Competitor**: Tracks competitors and their participation in games.
7. **Medal**: Stores medal information (Gold, Silver, Bronze).
8. **NOC Region**: Links National Olympic Committees (NOCs) to regions.
9. **Person**: Stores personal details of participants, including height, weight, and gender.
10. **Person Region**: Links individuals to their regions.
11. **Sport**: Contains details about sports and their classifications.

---

## Problem Statements
This project addresses multiple problem statements using Power BI and SQL to analyze and visualize the data.

### Power BI Analysis
1. **Olympic Games Overview**:
   - Number of Olympic Games held in each season (Summer vs. Winter).
   - Distribution of games across decades.
   - Cities with the highest number of hosted games.
     ![image](https://github.com/user-attachments/assets/65b50f7f-72a6-408f-9955-28a0e42c3105)

2. **Sports and Events Analysis**:
   - Distribution of sports between Summer and Winter Olympics.
   - Sports with the highest number of events.
   - Evolution of participation in each sport over time.
   - Distribution of events by gender (Men, Women, Mixed).
3. **Participant Analysis**:
   - Distribution of participants by gender.
   - Age distribution of participants across games.
   - Countries with the highest number of participants.
4. **Medal Analysis**:
   - Medals awarded in each Olympic Games.
   - Countries with the highest number of gold medals.
   - Medal distribution across different sports and regions.
5. **Regional Analysis**:
   - Number of NOCs participating in each Olympic Games.
   - Regions with the highest number of participants.

### SQL-Based Exploratory Data Analysis (EDA)
1. Trends in hosting Olympic Games.
2. Changes in the duration of games over time.
3. Emerging and discontinued sports/events.
4. Trends in participant height and weight.
5. Regional dominance in specific sports or events.
6. Factors contributing to performance and success.
7. Cultural and geographical influences on regional performance.

---

## Methodology

### Steps
1. **Data Preparation**:
   - Load and clean the Olympic dataset.
   - Establish relationships between tables based on the ER diagram.
2. **Power BI Visualization**:
   - Design dashboards to visualize trends, distributions, and comparisons.
   - Implement filters for dynamic exploration.
3. **SQL Querying**:
   - Write queries to perform in-depth EDA and answer key questions.
4. **Analysis Segmentation**:
   - Games Analysis
   - Sports Analysis
   - Event Analysis
   - Participant Analysis
   - Medal Analysis
   - Regional Analysis

### Tools Used
- **Power BI**: For dashboard creation and visualization.
- **SQL**: For exploratory data analysis.

---

## Results and Insights
1. Identified trends in the hosting of Summer and Winter Olympics.
2. Explored the evolution of sports, events, and participation over decades.
3. Analyzed gender distribution and highlighted sports/events with significant gender disparity.
4. Identified countries and regions with consistent performance and notable achievements.
5. Discovered the impact of cultural and geographical factors on Olympic outcomes.

---

## Next Steps
1. **Games Analysis**:
   - Dive deeper into the frequency and distribution of games.
   - Explore notable events and occurrences.
2. **Sports Analysis**:
   - Focus on emerging and discontinued sports.
   - Analyze the popularity of sports across decades.
3. **Event Analysis**:
   - Investigate the evolution of events by gender and type.
4. **Participant Analysis**:
   - Study demographic trends and performance variations.
5. **Medal Analysis**:
   - Evaluate factors influencing medal success.
   - Explore unexpected wins and emerging trends.
6. **Regional Analysis**:
   - Examine growth and decline in regional participation.
   - Assess the impact of specific regions on overall medal tallies.

---

## Conclusion
This project provides a comprehensive analysis of the Olympic Games, offering actionable insights for researchers, policymakers, and sports organizations. The integration of Power BI and SQL allows for both dynamic visualization and in-depth exploration, ensuring a holistic understanding of the data. By addressing various problem statements, the project highlights historical trends, regional impacts, and the evolution of the Olympics over time.

