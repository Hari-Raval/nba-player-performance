# Understanding NBA Team and Player Performance

## Overview 

The NBA (National Basketball Association) is an organization which negotiates the varying interests of players, coaches, owners, and fans. One area of common interest is understanding team and player performance. Teams can obtain insights into their level of play and make decisions on personal changes. Fans can use these insights to engage in the betting market. Analysis of NBA game data from 2004 to 2020 uncovers a complex team network and latent player positions. 

In this work, we use classification models to predict the outcome of 24,196 games and regression models to predict the impact 2,407 players have on games. We aid these prediction tasks by building digraphs of team networks based on game outcomes and creating new features via clustering on a reduced dimension data set of players. We find that logistic regression achieves an accuracy of 84.89\% in predicting game outcome when including network-based features and ridge regression performs best in predicting player impact when using cluster label features. 

## Approach and Results

The overall approach taken in this project as well as key results are detailed [here](https://github.com/Hari-Raval/nba-player-performance/blob/main/report_results.pdf). For a quicker snapshot of the project results, one can view the poster shown [here](https://github.com/Hari-Raval/nba-player-performance/blob/main/poster.png)


