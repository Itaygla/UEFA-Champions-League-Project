# UEFA Champions League Project

## Overview
As a prospective sponsor interested in the football industry, how can I determine the most efficient sponsorship opportunities within the UEFA Champions League?

To answer this question, I considered several key factors:

- **Team and Player Performance:** Consider the performance of teams and players in the league, as successful teams and star players often attract more attention and provide better sponsorship opportunities.
- **Stadium:** Evaluate the stadiums and venues where matches are held. Larger-capacity venues can offer more exposure and fan engagement opportunities.
- **Team Reputation:** Examine the reputation and fan following of teams within the UEFA Champions League, as well as their historical performance in the league.
- **Nationality and Demographics:** Consider the nationality and demographics of both teams and players.
- **Competitive Highlight:** Analyze the competitive highlight to understand better which different categories give us more indicators for sponsors' investment.

## Data Understanding

### Context
UEFA Champions League (UCL) is one of the biggest football competitions conducted by the Union of European Football Association. Started in 1955, UCL is one of the world's most viewed and anticipated football tournaments.

### Content
This dataset contains teams, player details, player stats and records, team managers, matches and their results, goals, stadiums, and more from 2016 to 2022.

#### Goals.csv
Includes the following columns:
- `GOAL_ID`: unique value of each goal
- `MATCH_ID`: unique value of each match
- `PID`: unique value of each player who scored the goal
- `DURATION`: the minute the player scores the goal
- `ASSIST`: player ID that makes the assist
- `GOAL_DESC`: goal description

#### Matches.csv
Includes the following columns:
- `MATCH_ID`: unique value of the match
- `SEASON`: season the match was played
- `DATE_TIME`: the date and the hour the match was played
- `HOME_TEAM`: the team host
- `AWAY_TEAM`: the foreign team
- `STADIUM`: where the match was played
- `HOME_TEAM_SCORE`: the number of goals for the home team
- `AWAY_TEAM_SCORE`: the number of goals for the away team
- `PENALTY_SHOOT_OUT`: if the match ended with penalty shootouts
- `ATTENDANCE`: number of viewers in the stadium

#### Players.csv
Includes the following columns:
- `PLAYER_ID`: unique value of each player
- `FIRST_NAME`: first name of the player
- `LAST_NAME`: last name of the player
- `NATIONALITY`: the origin of his country
- `DOB`: date of birth
- `TEAM`: the team player belongs to
- `JERSEY_NUMBER`: the number on his shirt
- `POSITION`: which position the player is on the field

#### Stadiums.csv
Includes the following columns:
- `NAME`: name of the stadium
- `CITY`: the city of the stadium
- `COUNTRY`: the country of the stadium
- `CAPACITY`: the capacity of the stadium

#### Teams.csv
Includes the following columns:
- `TEAM_NAME`: name of the team
- `COUNTRY`: the country of the team
- `HOME_STADIUM`: name of her stadium

#### Managers.csv
Includes the following columns:
- `FIRST_NAME`: first name of the coach
- `LAST_NAME`: last name of the coach
- `NATIONALITY`: the origin of his country
- `DOB`: date of birth
- `TEAM`: the team coach belongs to

## Questions

### Player Performance:
- Who are the top 10 scorers?
- Who has won the Golden foot award in each season?
- Who are the top 10 players who assisted the most?
- Who are the top 10 players who assisted the most by seasons?

### Stadium:
- Which top 5 stadiums have the biggest capacity?
- Top 10 stadiums with the most amount of attendance?
- Home success rate?

### Team Reputation:
- How many wins for each team?
- How many wins for the host and foreign teams?

### Nationality and Demographics:
- Nationality of key players?
- Most goals per country?
- Number of players per nationality?

### Competitive Highlight:
- Which player has the most goals in different categories of goal descriptions?
- How many goals were scored in different parts of the game?
- Number of goals per minute?
- Goals per stadium?


## Conclusion And Recommendations

### Key players from the seasons 2016 to 2022 (including best scorers and assists):
- Robert Lewandowski
- Cristiano Ronaldo
- Lionel Messi
- Karim Benzema
- Mbappe Kylian
- Neymar

### Best Stadium (including home wins and attendance):
- Spotify Camp Nou
- Old Trafford
- Santiago Bernabeu
- Etihad Stadium
- Allianz Arena

### Teams with a high reputation (including goals per country and the number of national players):
- Bayern Munchen
- Real Madrid
- Manchester City
- Juventus
- Liverpool FC

### Most influential nationalities (including goals and players):
- Germany
- England
- Spain
- Italy
- France

## Report And Presentation


[Link to Tableau.]([https://github.com](https://public.tableau.com/app/profile/itay.glantzen/viz/ProjectUefachampionsleage/TeamandPlayerPerformence))

## Reference

### Key players

#### Top 5 scorers players
1. Robert Lewandowski (54 goals)
2. Cristiano Ronaldo (47 goals)
3. Lionel Messi (42 goals)
4. Karim Benzema (40 goals)
5. Mbappe Kylian (33 goals)

#### Golden foot Players
- Cristiano Ronaldo (12) - season 2016-2017
- Cristiano Ronaldo (15) - season 2017-2018
- Lionel Messi (12) - season 2018-2019
- Robert Lewandowski (15) - season 2019-2020
- Erling Haaland (10) - season 2021-2022
- Karim Benzema (15) - season 2021-2022

#### Top assists players
1. Neymar (24 assists)
2. Mbappe Kylian (21 assists)
3. Kevin De Bruyne (18 assists)
4. Angel Di Maria (17 assists)
5. Raheem Sterling (17 assists)

#### Top assists players by season
- Neymar (9) - season 2016-2017
- Minlner (8) - season 2017-2018
- Alba, Mbappe, Sane, Tadic (5) - season 2018-2019
- Mbappe, Lewandowski, Di Maria (6) - season 2019-2020
- Cuardraro (6) - season 2021-2022
- Fernandes (7) - season 2021-2022

### Stadiums

#### Stadiums with the biggest capacity
1. Spotify Camp Nou (99354)
2. Wembley Stadium (90000)
3. Signal Iduna Park (81365)
4. Stade de France (81338)
5. Santiago Bernabeu (81044)

#### Average amount of attendance
1. Old Trafford (73690)
2. Spotify Camp Nou (73660)
3. Wembley
