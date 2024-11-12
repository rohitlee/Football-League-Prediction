<!-- PROJECT LOGO -->
<p align="center">
    <img src="images/favicon.svg" alt="Logo" width="80" height="80">
  <h3 align="center">Football League Predictions</h3>
</p>

<!-- ABOUT THE PROJECT -->

## About The Project
Football is one of the world’s most popular sports, attracting the interest of fans, coaches, media, and sports analysts. Predicting match outcomes is a complex challenge due to the many variables influencing results. This unpredictability, coupled with the analytical opportunities it presents, has fueled the development of predictive models to support sports analytics. In this study, we apply machine learning techniques to analyze various statistics from previous matches along with player attributes from both teams to forecast match outcomes. Multiple predictive models were tested, with experimental results showing promising accuracy and insights for sports analysis.

This presents an opportunity to create more advanced forecasting tools that predict the most probable outcome of a football match and provide confidence levels for each result, leading to more informed insights. Football match outcomes can be anticipated by analyzing historical data from past seasons. With the increasing availability of detailed data across various football leagues, it is possible to collect diverse features for analysis. In this study, we apply machine learning (ML) algorithms to predict football match outcomes, using multiple features that include match statistics and attributes of players from both teams.

## Related work
While the unpredictability of sports is well known, the football world occasionally witnesses results that defy expectations—such as Leicester City’s stunning English Premier League title win in the 2015/16 season. A detailed <a href="https://dl.acm.org/doi/10.1145/3097983.3098121">investigation</a> was conducted to explore the factors contributing to this remarkable success and to improve future prediction methods. Key findings highlighted Leicester's exceptional goalkeeper performance and their efficiency in counter-attacking. Additionally, several Leicester players consistently intercepted passes with a high probability of completion (over 80%). This case study also led to the development of a model to predict a team’s shots and goals during a game. The analysis revealed that models incorporating shot types (e.g., counter-attacks, shots from crosses into the penalty area) achieved more accurate predictions.

Another <a href="https://www.researchgate.net/publication/257569396_Football_Mining_with_R">study</a> analyzed data from the 2010/11 Italian Serie A season, using 300 games for training and 80 for testing. One key conclusion was that teams frequently relying on aerial plays were more likely to draw or lose matches. Further <a href="https://www.mdpi.com/2076-3417/10/1/46">research</a> explored machine learning to forecast football match outcomes based on match and player attributes. A simulation study, covering all matches from the top five European football leagues and their second divisions between 2006 and 2018, found that an ensemble approach significantly improved prediction accuracy and offered valuable insights for analyzing match outcomes.

## Problem Statement
The analysis revealed that studies with lower model performance often lacked variables that effectively capture key characteristics of players and the dynamics of the game. Additionally, it is crucial for models to be trained on data spanning multiple seasons, as teams tend to undergo significant changes each season, affecting performance and outcomes.

## Analysis and Processing of Data
### Data Description
The data for this project was collected by scraping historical football match statistics from the website <a href="https://fbref.com/en/comps/9/Premier-League-Stats">FBRef</a>. 
A dataset of 1660 football matches across five seasons, from 2020/2021 to 2024/2025, was collected. However, since only seven games had been played in the ongoing 2024/2025 season at the time of data collection, data from this season was excluded from the analysis. The remaining 1520 matches pertain to the top tier of English football, officially known as the Premier League. Out of these games, the home team won 666 times (20.94%), 340 matches ended in a draw (10.69%), and the away team won 514 times (16.16%).
