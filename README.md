# fpl

## Matchups

This makes it easier to compare the goal scoring situations of two teams, and can be used to find out when a team particularly good at 
something is facing a team that it particularly bad at it. For example, Team A are the 3rd best in the league at attacking from 
set-pieces/open-play/counter-attacks, and they face Team B, who have conceeded the most goals from set-pieces/open-play/counter-attacks. 

This was created to find out when to start Tomas Soucek, a budget midfielder who scores a lot of headers in my Fantasy team. I only want him to start against teams that are bad at set pieces. 

The input data is a csv that can be downloaded from [whoscored.com](https://www.whoscored.com/Regions/252/Tournaments/2/Seasons/8228/Stages/18685/TeamStatistics/England-Premier-League-2020-2021) plus 
the list of fixtures of the week. 

The output data is a printout of strengths of each team in a matchup, e.g. 
```
Crystal Palace better at:  Setpiece_rank 
Leicester better at:  Openplay_rank Penalty_rank 
```

### To add
+ Automatic importation of data and fixtures from Whoscored.com
+ More customization for various leagues, etc
+ Taking into account recent form or big outliers or hidden stats (xG)
