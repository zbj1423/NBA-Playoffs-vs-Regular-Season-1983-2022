# NBA-Playoffs-vs-Regular-Season-1983-2022

## Introduction
Watching playoff games in the NBA often feels very different from watching most regular season games. Accordingly, a lot of popular claims are made about playoff basketball: higher intensity, players play harder, defenses are better, more gameplan adjustments, slower pace, etc. This project compiled team stats from the past 40 seasons of the NBA (using [nba_api](https://github.com/swar/nba_api)) to obtain quantitative measures of how playoffs differ from the regular season.

## Results
The major differences in stats between playoffs and regular season (see graphs below for exact values): average points and offensive rating go down in the playoffs. Defensive rating goes up. All shooting percentage stats go down. More fouls are called and more free throws attempted. Teams have less turnovers and less total possessions. Assist stats all decrease, so maybe more iso-heavy possessions. Also, an interesting effect of playoff teams in 80s and 90s attempting more 3s in the playoffs vs. regular season compared to teams from 2007-2022.

![alt text](https://i.imgur.com/SJ2AtBh.png "barGraphs_playoffsMinusRegSeason")


## Data and Methods
All data was collected using the [nba_api](https://github.com/swar/nba_api). The dataset consists of per-game stat averages for all teams starting from the 1983-84 season through the 2021-22 season. In total: 1103 regular season teams, 624 of which made the playoffs in their respective years. Traditional stats include: PTS, FGM, FGA, FG_PCT, FG3M, FG3A, FG3_PCT, FTM, FTA, FT_PCT, OREB, DREB, REB, AST, STL, BLK, TOV, PF, PLUS_MINUS. Advanced stats include: NET_RATING, OFF_RATING, DEF_RATING, EFG_PCT, TS_PCT, PACE, OREB_PCT, DREB_PCT, REB_PCT, AST_PCT, AST_TO, AST_RATIO, TM_TOV_PCT. Note: for plus/minus and all of the advanced stats, I could only get data beginning from the 1997-98 season onwards, which resulted in 743 total regular season teams, 400 of which made the playoffs. 
