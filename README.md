# Data-115
Motivation:

As a fan of Manchester United in England's Premier League, the team has not performed very well in the past few seasons. However, the team has cultivated several outstanding young players, such as Marcus Rashford, Mason Greenwood, Brandon Williams, etc. Young players have always been the future of the team. Even when the team's record is not good, all teams in the Premier League will not ignore the cultivation of young players. However, in recent years, all teams in the Premier League have paid special attention to the offensive ability of all defensive staff. Therefore, I want to observe which team in the Premier League has the best overall performance in goal efficiency and assist efficiency among defensive players under the age of 25 (including 25 years old)?

Data Sources：

I get the personal statistics of the 2019-2020 England Premier League from the website FBREF. The total number of players in the whole league reached 522, but when converted to file. CSV, I don't know why 23 people were lost. After inspection, these 23 people are not within the age range of 18-25 and are not within the scope of this survey.

Processing Steps：

First, clean up the converted data files and delete some invalid data such as yellow cards, number of stars, number of fouls, and so on. Finally, 9 columns of player, POS (position), square (the name of team), age, MP (match play), min (minutes), GLS (goals), AST (assistants), and PK are reserved. The personnel data for this analysis were determined by screening the age (18-25) and the player's position on the field (DF). A total of 98 people from 20 different clubs are eligible. Then we added three items: G90 (goal efficiency), a90 (assist efficiency) and T90 (total efficiency) to help us more intuitively determine the efficiency value of these players through numbers.
![This is an image](https://github.com/Ziwen77/Data-115/blob/27bf61265df59791b0ae063b2a11c149b7cff2c0/T90.jpg)

Visualization：

After processing the data, the player's playing time and T90 value, the team's T90 average data, and T90 total data are displayed by histogram and scatter diagram respectively.

![This is an image](https://github.com/Ziwen77/Data-115/blob/27bf61265df59791b0ae063b2a11c149b7cff2c0/T90-Min.jpg)

![This is an image](https://github.com/Ziwen77/Data-115/blob/27bf61265df59791b0ae063b2a11c149b7cff2c0/T90%20of%20Team.jpg)

![This is an image](https://github.com/Ziwen77/Data-115/blob/27bf61265df59791b0ae063b2a11c149b7cff2c0/Average%20of%20T90.jpg)

Analysis:

Through the data, I found that the overall efficiency of Andrew Robertson of Liverpool reached 0.45%, followed by 0.43% of Moussa  Djenepo of Southampton. Among the Premier League teams, Southampton has the highest overall efficiency, reaching 1.25%, followed by 0.99% of Leicester City and 0.96% of Arsenal. Therefore, among all the teams in the Premier League, Southampton is the team with the best overall performance in goal efficiency and assist efficiency among the defensive players under the age of 25 (including 25). However, in the process of making icons, it was unexpectedly found that the highest average data of T90 was Leicester City. After checking the team data, it is found that Southampton's efficiency is due to the high performance of individual players. However, Leicester City has eight players in this analysis range, half more than Southampton on the list. They all have better playing time and efficiency. Therefore, in my opinion, Southampton is the best defensive player under the age of 25 in the Premier League in terms of goal efficiency and assists efficiency. Leicester City prefers to use young players. If I were an agent, I would recommend young players to Leicester City.

References:

https://fbref.com/en/comps/9/3232/possession/2019-2020-Premier-League-Stats
