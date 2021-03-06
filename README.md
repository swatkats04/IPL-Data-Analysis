# IPL-Data-Analysis

## About The Project
In this project we will we will perform Exploratory Data Analysis on IPL matches and also look into interesting insights for these matches.

## Dataset
The dataset consists of data about IPL matches played from the year 2008 to 2019. The IPL is a professional T20 cricket league founded by the Board of Control for Cricket in India (BCCI) in 2008. The league comprises of 8 teams representing 8 different Indian cities or states. For our analysis we will use the matches.csv from the Dataset folder.
The dataset consists 18 columns. Let’s get familiar with the columns.
* __id:__ The IPL match id.
* __season:__ The IPL season
* __city:__ The city where the IPL match was held.
* __date:__ The date on which the match was held.
* __team1:__ One of the teams of the IPL match
* __team2:__ The other team of the IPL match
* __toss_winner:__ The team that won the toss
* __toss_decision:__ The decision taken by the team that won the toss to ‘bat’ or ‘field’
* __result:__ The result(‘normal’, ‘tie’, ‘no result’) of the match.
* __dl_applied:__ (1 or 0)indicates whether the Duckworth-Lewis rule was applied or not.
* __winner:__ The winner of the match.
* __win_by_runs:__ Provides the runs by which the team batting first won
* __win_by_runs:__ Provides the number of wickets by which the team batting second won.
* __player_of_match:__ The outstanding player of the match.
* __venue:__ The venue where the match was hosted.
* __umpire1:__ One of the two on-field umpires who officiate the match.
* __umpire2:__ One of the two on-field umpires who officiate the match.
* __umpire3:__ The off-field umpire who officiates the match

## Objectives
* To find the team that won the most number of matches in a season.
* To find the team that lost the most number of matches in a season.
* Does winning toss increases the chances of victory.
* To find the player with the most player of the match awards.
* To find the city that hosted the maximum number of IPL matches.
* To find the most winning team for each season.
* To find the on-field umpire with the maximum number of IPL matches.
* To find the biggest victories in IPL while defending a total and while chasing a total.

## Repo structure
+ [`Dataset`](/Dataset/): Contains the matches.csv data for our analysis.
+ [`IPL_Analysis.ipynb`](/IPL_Analysis.ipynb/): Contains the Google Colab notebook of our project.
