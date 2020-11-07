# Introduction

This project and the data explores the relationship between Social Media, Salary, Influence, Performance and Team Valuation in the NBA.  This is covered in [Chapter 6 of Pragmatic AI](https://amzn.to/2LFLVEg)

## Strata 2018 Talk

* [What is the relationship between social influence and the NBA](https://conferences.oreilly.com/strata/strata-ca/public/schedule/detail/63606)

* [Slides on What is the relationship between social influence and the NBA](https://cdn.oreillystatic.com/en/assets/1/event/269/What%20is%20the%20relationship%20between%20social%20influence%20and%20the%20NBA_%20Presentation.pdf)

* [Video of Strata Talk on Safari](https://www.safaribooksonline.com/library/view/strata-data-conference/9781492025955/video319171.html)

## IBM Developerworks Articles on Project

* *Explore valuation and attendance using data science and machine learning*:  https://www.ibm.com/developerworks/library/ba-social-influence-python-pandas-machine-learning-r-1/

* *Exploring the individual NBA players*:  https://www.ibm.com/developerworks/analytics/library/ba-social-influence-python-pandas-machine-learning-r-2/

## Kaggle Version of Project

You can also see Kaggle Notebooks here:  

* [Kaggle Kernel NBA Player Influence, Salary and Performance ](https://www.kaggle.com/noahgift/nba-player-power-influence-and-performance)

* [Kaggle Kernel Team Valuation Performance ](https://www.kaggle.com/noahgift/nba-team-valuation-exploration)

## Data Legend

### [Exploring Team Valuation Notebook](https://github.com/noahgift/socialpowernba/blob/master/notebooks/exploring_team_valuation_nba.ipynb)

This notebook has the following data legend:

### [Exploring Team Valuation Dataset created](https://github.com/noahgift/socialpowernba/blob/master/data/nba_2017_att_val_elo_win_housing_cluster.csv)

* TEAM:  Name of the NBA Team
* GMS:  Games Played
* PCT_ATTENDANCE:  Average % Attendance of capacity (note some teams were over capacity as an averag)
* WINNING_SEASON:  If the team won over 50% of their games, it was 1, otherwise 0.
* TOTAL_ATTENDANCE_MILLIONS:  Total season attendance in the millions.
* VALUE_MILLIONS:  Valuation of the team in millions
* ELO:  https://en.wikipedia.org/wiki/Elo_rating_system
* CONF:  Eastern or Western Conference
* COUNTY:  The county where the team is located
* MEDIAN_HOME_PRICE_COUNTY_MILLIONS:  Median Home Price
* COUNTY_POPULATION_MILLIONS:  The Population of the county in Millions
* cluster:  A cluster created by KMeans clustering (shown in notebook)

### [Exploring Team Valuation Notebook](https://github.com/noahgift/socialpowernba/blob/master/notebooks/nba_player_power_influence_performance.ipynb)

### [Exploring Team Valuation Dataset created](https://github.com/noahgift/socialpowernba/blob/master/data/nba_2017_endorsement_full_stats.csv)

* PLAYER:  NBA Player Name
* TEAM:  NBA Team
* SALARY_MILLIONS:  Salary paid to player in Millions
* ENDORSEMENT_MILLIONS:  Endorsements paid to player in Millions
* PCT_ATTENDANCE_STADIUM:  Average % attendance in stadium
* ATTENDANCE_TOTAL_BY_10K
* FRANCHISE_VALUE_100_MILLION
* ELO_100X:  https://en.wikipedia.org/wiki/Elo_rating_system/100
* CONF:  Eastern or Western Conference (Even split between all teams between both conferences)
* POSITION:  Position of the player
* AGE
* MP:   Minutes/Games Average
* GP:  Games played
* MPG:  Minutes/Games Average
* WINS_RPM:  Wins attributed to individual player performance.  One of the best metrics of overall impact on team.
* PLAYER_TEAM_WINS:  Wins for the team the playes is on.  
* WIKIPEDIA_PAGEVIEWS_10K:  Pageviews of player divided by 10 thousand
TWITTER_FAVORITE_COUNT_1K:  Twitter favorites of player profile divided by 1 thousand.

# Social Power, Influence and Performance in the NBA
Social Power in the NBA (Comparing on the court performance with Social Influence)

![Social Power Data Sources](https://user-images.githubusercontent.com/58792/28694940-19e6e532-72e1-11e7-9b62-0796e8ea140b.png)

# Data Exploration

## Player Impact Estimation
![NBA 2016-2017 Season PIE](https://user-images.githubusercontent.com/58792/28027382-bd7f5108-654d-11e7-8ed1-299a880714cd.png)

## Social Power, Performance and Salary
![NBA 2016-2017 Season Twitter, Salary and Performance](https://user-images.githubusercontent.com/58792/28044183-b873238c-658a-11e7-90b7-bd923aeb1e32.png)

## Valuation vs Attendance

![NBA 2016-2017 Season Valuation Vs Attendance](https://user-images.githubusercontent.com/58792/28756721-c213f670-7528-11e7-8988-366b461e8992.png)

## ELO vs Attendance

![NBA 2016-2017 ELO Score Vs Attendance](https://user-images.githubusercontent.com/58792/28759207-2b139d9e-754f-11e7-9695-9a9083e1fb9c.png)

## ELO Correlation Heatmap 

![NBA 2016-2017 ELO, Attendance, Valuation Heatmap](https://user-images.githubusercontent.com/58792/28759996-25da9680-7558-11e7-9168-85989b7d63c9.png)

## REAL PLUS MINUS Wins, POINTS and SALARY
![NBA 2016-2017 REAL PLUS MINUS Wins, POINTS and SALARY](https://user-images.githubusercontent.com/58792/28798971-5bf50158-75fb-11e7-9090-290b0703b2aa.png)

## 3D Plot
![3D Plot](https://user-images.githubusercontent.com/58792/36056809-7f87a266-0dbc-11e8-8877-9bb87905adbd.png)

## ALL Data Correlation Heatmap

![NBA 2016-2017 Correlation Heatmap REAL PLUS MINUS Wins, POINTS, SALARY, Wikipedia, Twitter](https://user-images.githubusercontent.com/58792/28804798-423a049c-761a-11e7-92ca-bc60bec6c147.png)

## Explore Juypter Notebooks

[Juypter Noteboooks Social Power](https://github.com/noahgift/socialpowernba/tree/master/notebooks)

## Social Money

![NBA 2016-2017 Social Power, Influence and Performance Heatmap](https://user-images.githubusercontent.com/58792/28856405-adc4dd8a-76f7-11e7-8d9a-08d3b04369de.png)

## Social Power and Performance
![NBA 2016-2017 Social Power and Performance Heatmap](https://user-images.githubusercontent.com/58792/28851989-e80b35f6-76da-11e7-9497-1f69dc3c1134.png)

![NBA 2016-2017 Social Power and Performance Correlation Heatmap](https://user-images.githubusercontent.com/58792/28857433-4f640d04-76fe-11e7-9b44-808df9f32c5a.png)

## Explore Raw Data Here

* [NBA 2016-2017 REAL PLUS MINUS Wins, POINTS, SALARY, Wikipedia, Twitter](https://github.com/noahgift/socialpowernba/blob/master/data/nba_2017_players_with_salary_wiki_twitter.csv) 
  - This data was collected from multiple sources:  ESPN, Basketball-Reference, Twitter, Wikipedia, and Forbes
  
  ### Additional Related Topics from Noah Gift

His most recent books are:

*   [Pragmatic A.I.:   An introduction to Cloud-Based Machine Learning (Pearson, 2018)](https://www.amazon.com/Pragmatic-AI-Introduction-Cloud-Based-Analytics/dp/0134863860)
*   [Python for DevOps (O'Reilly, 2020)](https://www.amazon.com/Python-DevOps-Ruthlessly-Effective-Automation/dp/149205769X). 

His most recent video courses are:

*   [Essential Machine Learning and A.I. with Python and Jupyter Notebook LiveLessons (Pearson, 2018)](https://learning.oreilly.com/videos/essential-machine-learning/9780135261118)
*   [AWS Certified Machine Learning-Specialty (ML-S) (Pearson, 2019)](https://learning.oreilly.com/videos/aws-certified-machine/9780135556597)
*   [Python for Data Science Complete Video Course Video Training (Pearson, 2019)](https://learning.oreilly.com/videos/python-for-data/9780135687253)
*   [AWS Certified Big Data - Specialty Complete Video Course and Practice Test Video Training (Pearson, 2019)](https://learning.oreilly.com/videos/aws-certified-big/9780135772324)
*   [Building A.I. Applications on Google Cloud Platform (Pearson, 2019)](https://learning.oreilly.com/videos/building-ai-applications/9780135973462)
*   [Pragmatic AI and Machine Learning Core Principles (Pearson, 2019)](https://learning.oreilly.com/videos/pragmatic-ai-and/9780136554714)
*   [Data Engineering with Python and AWS Lambda (Pearson, 2019)](https://learning.oreilly.com/videos/data-engineering-with/9780135964330)

His most recent online courses are:

*   [Microservices with this Udacity DevOps Nanodegree (Udacity, 2019)](https://www.udacity.com/course/cloud-dev-ops-nanodegree--nd9991)
*   [Command Line Automation in Python (DataCamp, 2019)](https://www.datacamp.com/instructors/ndgift)
