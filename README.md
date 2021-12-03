ML-for-Good-Hackathon
Team : Data Miners (Team 11)

Project Overview
The objective of this project is to analyze and extract insights from the survey responses on the Coronavirus Health and Impact (CRISIS)

Data Sources
- ProlifiAcademic (Adult and Parent datasets)
- CrisisLogger
- FocusGroups (social Groups and Gaming Groups)

Key Methodology
- EDA and Visualizations
- Identification of key themes through Topic Modeling
- Identification of likely predictors using Random Forest
- Sentiment Analysis
- Hypothesis testing (Kruskal walis)

Key Observations

For ProlificAcademy Adult Dataset:
1. Downward trend in Covid worry and emotions/mental stress from April 2020 to April 2021
2. Covid worry and emotions/mental stress are positively correlated
3. For Country=186, emotions/mental stress was overall less than in Country=187
4. For Country=186, covid worries was overall more than in Country=187
5. Top 5 factors that affected emotions and mental states:
- In April 2020: Covid worries, 3 months prior emotion state, Life Changes, Mental Health and current Media use
- In May 2020: Life Changes, Covid worries, in person conversation impact, current Media use and positive Changes
- In November 2020: Life Changes, Covid worries, current Media use,in person conversation impact use and time spent outside
- In April 2021, Life Changes, Covid worries, rooms in house and internet addiction
As the covid worries are reducing, it's not the most important factor that affactes mental state
6. Adults who are not parent seem to be more stressed in April 2021

For Social Groups Dataset:
1. Key themes
1.1. Social Groups 1 - more time at hand,lock down,social media and online games
1.2. Social Groups 2 - social life restrictions, lockdown,time spent on phone,social media
1.3. Social Groups 3 - Remote working and schooling, anxiety, social life restrictions, struggles
1.4. Social Groups 4 - technology use, time spent online, video games
2. Sentiment Analysis
2.1. Social Groups 1 - neutral
2.2. Social Groups 2, 3, 4 - Moderately negative

For Gaming Groups Dataset:
1. Key themes
1.1. Gaming Groups 1 - more time at hand,time spent online,social life
1.2. Gaming Groups 2 - experiences,time spent online, covid worries, family life, podcast
1.3. Gaming Groups 3 - Covid worries,more time at hand,time spent online, remembering pre-covid times, remote schooling
1.4. Gaming Groups 4 - Frustration, social life, Online games
2. Sentiment Analysis
2.1. Gaming Groups 1 - very little negative
2.2. Gaming Groups 2 - little negative
2.3. Gaming Groups 3, 4 - Moderately negative


Additional observations are mentioned in the respective notebooks.
