# DETECT ANOMALIES IN PLAYER POINTS SCORED WHEN TEAM LISTED AS BETTING FAVORITE MISSED BETTING SPREAD <br> # BY OLUTOSIN FASHUSI
• <b> PTS: </b> Points Scored <br> 
• <b> PREV AVG PTS: </b> Previous Avg Points Scored To Date <br> 
• <b> TEAM: </b> Team abbreviation <br> 
• <b> DATE:  </b> Game Date <br> 
• <b> OPPT: </b> Match opponent abbreviation <br> 
• <b> GAMEID: </b> Every NBA game has a unique GAMEID <br> 
• <b> GAME PTS DELTA: </b> Difference between points scored by TEAM & points scored by OPPT<br> 
• <b> SPREAD: </b> Betting spread for TEAM (minus sign indicates team is the favorite) <br> 
• 🚩: </b> Flagged Occurrence  <br><br>
<b><i>EXAMPLE:</b></i> Index 0 shows on 2024-01-13 Atlanta Hawks played Washington Wizards & were the betting favorite to win by 8 or more points & Jalen Johnson missed his average points scored of 15.4 by 10.4 as he scored 5.
![anomalyDetection](https://github.com/user-attachments/assets/859d0dcc-e304-4b0e-928e-d39a07603cfe)
# OBJECTIVES:
• Inspect all 1230 NBA games played during 2023-24 NBA Regular Season & detect when the player on team listed as betting favorite misses their average points scored by at least 10
# DATA SOURCES: 
<b><i>NBA.com</i></b><br>
&nbsp;&nbsp;&nbsp; [2023-24 Regular Season Box Scores](https://www.nba.com/stats/teams/boxscores?Season=2023-24&SeasonType=Regular%20Season&dir=A&sort=GDATE) <br>
<br>
<i><b>VEGASINSIDER.com</i></b><br>
&nbsp;&nbsp;&nbsp; [NBA Odds & Betting Lines](https://www.vegasinsider.com/nba/odds/las-vegas) 
<br>
# CONCLUSIONS:
• Identified 592 games where team listed as betting favorite missed beating spread <br>
• Examined 564 players that played in the 592 games & flagged 219 such irregularities when player on betting favorite team player on betting favorite team misses their average points scored by at least 10  <br>
• Identified Players With Multiple Occurrences: 
![players](https://github.com/user-attachments/assets/94c34736-5005-4e0c-8f98-2544ee29638b)
