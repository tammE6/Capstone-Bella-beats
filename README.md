# Capstone-Bella-beats
Case Study 
# Bellabeats Case Study

## Project Overview
# Bellabeats Case Study

## Project Overview
The purpose of this Bellabeat project is to analyze smart device usage data to uncover trends in consumer health habits—specifically related to physical activity and sleep. By examining Fitbit data, the goal is to generate actionable insights that Bellabeat can apply to its marketing strategy, helping promote its wellness products more effectively. Ultimately, the analysis aims to support Bellabeat’s growth in the competitive smart wellness market by identifying behavior patterns that resonate with target users. 


## Table of Contents
Project Overview
Dataset(#dataset)
Tools Used(#tools-used)
Analysis Steps(#analysis-steps)
Findings(#findings)
Future Questions(#future-questions)
About Me(#about-me)

## Dataset
Source: Public Fitbit dataset from Kaggle
Participants: 30 Fitbit Users
Timeframe: 1 month of activity and sleep data
Files Used: dailyActivity_merged.csv-Steps, Calories, and activity minutes, minuteSleep_merged.csv-minute-level sleep data(aggregated to daily totals)
Type: Quantitative, time-series data
Key Metrics: Total Steps, Calories Burned, Activity Duration, Total Minute Asleep
Limitations: No demographic data (age, gender), small sample size, and collected in 2016 may not reflect current trends


 

## Tools Used
List all tools and software you used.  
R(tidyverse, ggplot2, )
Fitbit Dataset(30 users over 30 days)

## Analysis Steps

1. Ask
I defined the business task: Analyze smart device usage (Fitbit data) to identify user behavior trends and recommend how Bellabeat can apply these insights to promote one of its wellness products, such as the Leaf.

2. Prepare
I examined the publicly available Fitbit dataset from Kaggle, which included minute-level sleep data and daily activity metrics (steps, calories, activity time). I reviewed the data structure, checked its source credibility, and identified limitations such as small sample size (30 users) and lack of demographic details.

3. Process
In the processing phase, I utilized Python, specifically the pandas library, to meticulously clean and format the raw data. This involved several key steps, including converting all relevant date columns to a standard datetime format to ensure consistency and facilitate analysis. I then aggregated minute-level sleep data, transforming it into a more manageable daily summary of total minutes asleep per user. Finally, I merged the cleaned sleep and activity datasets based on unique user IDs and dates, while also removing any duplicate entries and columns that were not essential for the analysis.

4. Analyze
In the exploration phase, I delved into the cleaned dataset by generating various visualizations and summary statistics. This allowed me to calculate average daily steps and sleep duration, and subsequently examine the relationships between activity levels, calories burned, and sleep. Through this process, I was able to identify significant behavioral trends among users, such as prevalent low activity levels and suboptimal sleep durations.

5. Share
In the share phase, I created clear visualizations using Seaborn and Matplotlib to effectively communicate my findings. These included a bar chart showcasing average steps per user, a scatter plot illustrating the relationship between steps and calories burned, a histogram detailing sleep duration, and a line graph tracking daily steps and sleep over time. These compelling visuals were then integrated into the final report to convey key insights and provide strong support for the marketing recommendations.

6. Act
Based on the analysis, I recommended marketing strategies for Bellabeat to better position its products. These include behavior-based ad campaigns, habit-forming features, and audience segmentation targeting sleep and fitness-focused users.



## Findings
The analysis of Fitbit user data revealed several important trends in physical activity and sleep behavior. On average, most users recorded around 7,500 steps per day, with only a small percentage consistently reaching the recommended 10,000 steps. Users also spent a significant portion of the day in sedentary activity, suggesting that many do not meet daily movement goals. A strong positive correlation was observed between steps taken and calories burned, reinforcing the importance of physical activity in daily energy expenditure.

In terms of sleep, users averaged approximately 6.9 hours of sleep per night, falling short of the CDC’s recommended 7–9 hours. The data also showed a mild positive relationship between longer sleep duration and higher activity levels, implying that users who sleep more may also tend to be more active. These findings highlight opportunities for Bellabeat to position its products—especially the Leaf and Time—as tools to help users improve both sleep and movement habits.

## Future Questions
While this analysis revealed key trends in user activity and sleep, several areas remain unexplored due to data limitations. In future studies, it would be valuable to examine how health habits vary by gender or age group, as this could help Bellabeat tailor marketing strategies to specific segments. Additionally, exploring the impact of seasonal changes or weather conditions on activity levels could reveal time-based behavioral patterns. Longitudinal data over several months would also help assess the sustainability of user habits and the influence of factors like New Year’s resolutions.

Further, if Bellabeat had access to app engagement data, it would be insightful to explore which features drive the most user interaction—such as mindfulness sessions, hydration tracking, or menstrual health monitoring. Evaluating how goal-setting in the app affects wellness outcomes could also help improve personalized recommendations. Lastly, linking behavioral data with marketing performance metrics would allow Bellabeat to better understand which channels (e.g., Instagram, email, YouTube) are most effective in reaching different customer types. These questions represent opportunities for deeper, more targeted insights in future research.

## About Me
A line or two about yourself (optional).


