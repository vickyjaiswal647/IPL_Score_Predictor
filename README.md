
# IPL_Score_Predictor
# Dataset
### First inning ball to ball coverage of : 
* IPL matches -> data/IPL_Data.csv

# Each dataset consists of the following columns:
* mid -> Each match is given a unique number
* date -> When the match happened
* venue -> Stadium where match is being played
* bat_team -> Batting team name
* bowl_team -> Bowling team name
* batsman -> Batsman name who faced that ball
* bowler -> Bowler who bowled that ball
* runs -> Total runs scored by team at that instance
* wickets -> Total wickets fallen at that instance
* overs -> Total overs bowled at that instance
* runs_last_5 -> Total runs scored in last 5 overs
* wickets_last_5 -> Total wickets that fell in last 5 overs
* striker -> max(runs scored by striker, runs scored by non-striker)
* non-striker -> min(runs scored by striker, runs scored by non-striker)
* total -> Total runs scored by batting team after first innings
