<h1>FPL 22/23 Season Data Analysis</h1> 

<p>To view the Data Visualization in a better and interactive way: <a href = "https://nbviewer.org/github/ewaldo19/FPL-22-23-Data-Analysis/blob/3e3342279223c4c2b599eb1923052a94ca394217/FPL%202022-23%20Analysis.ipynb">Data Analysis - FPL 2022/23 Season</a></p>

<body><p align="justify">The aim for this project to display insights regarding the Fantasy Premier League for the 2022-2023 season. Being a football fan myself, this project of course gives me a sense of excitement. It's about digging into the details of player performances and team stats to help fellow fans make smarter decisions in their fantasy leagues. By focusing on the latest season, I want to uncover hidden patterns and provide practical tips that can make the Fantasy Premier League experience more enjoyable and rewarding.</p>

For beginners, there are some things you should know about how the players earn points in Fantasy Premier League:
| Action | Points Earned |
| ---------| ---------|
| Playing up to 60 mins  | 1 |
| Playing more than 60 mins (excluding stoppage time | 2 |
| Each goal scored by a Defender or Goalkeeper | 6 |
| Each goal scored by a Midfielder | 5 |
| Each goal scored by a Forward | 4 |
| Each assist for a goal | 3 |
| Each clean sheet by a Goalkeeper or Defender | 4 |
| Each clean sheet by a Midfielder | 1 |
| Every 3 shots saved by Goalkeeper | 1 |
| Each penalty save | 5 |
| Each penalty miss | -2 |
| Bonus points for the best players in a single match | 1-3 |
| Every 2 goals conceded by a Goalkeeper or Defender | -1 |
| Each yellow card | -1 |
| Each red card | -3 |
| Each own goal | -2 |

For more explanation about the rules, you can visit: <a href = "https://www.premierleague.com/news/2174909">Fantasy Premier League Regulations</a>

</body>

<h2>Cost vs Total Points</h2>
<img width="1000" alt="image" src="https://github.com/ewaldo19/FPL-22-23-Data-Analysis/assets/57058557/ea7f5301-53f3-41a2-9359-c940119c26de">
<br><br>
<p align = "justify">The provided scatter plot illustrates the correlation between a player's price and their point contributions. Evidently, there is a discernible trend indicating that higher-priced players tend to yield more points. This is exemplified by the top four most expensive players—Mohamed Salah, Erling Haaland, Kevin De Bruyne, and Harry Kane—who consistently produce the highest point totals.</p>

<div align = "center">
  <img src = "https://github.com/ewaldo19/FPL-22-23-Data-Analysis/blob/52d9ffeb7c33457a99aa35627f1a0c56784f5945/data/Prem%20Most%20Points.png">
</div>

<p align = "justify">However, exceptions exist, as some players with relatively high prices fail to meet performance expectations. Notably, Richarlison (FWD), priced at 8.4, only accumulated a modest 54 points. Despite amassing a cumulative score of 101 points, Raheem Sterling's performance fell short of expectations given his price of 9.7, particularly in terms of anticipated attacking contributions. And last but not least, Antony, a fresh face in the Premier League, managed only 82 points, a figure that doesn't align with his 7.2 price tag, thereby not meeting the expectations set for his performance.</p>

<div align = "center">
  <img src = "https://github.com/ewaldo19/FPL-22-23-Data-Analysis/blob/52d9ffeb7c33457a99aa35627f1a0c56784f5945/data/Prem%20Flops.png">
</div>

<h2>Most Valued Players</h2>
<h3>Goalkeepers</h3>
<img width="1000" alt="image" src="https://github.com/ewaldo19/FPL-22-23-Data-Analysis/assets/57058557/3dbb7689-b42e-4ead-817c-adce839d2b16">
<br><br>
<p align = "justify">The above chart shows the most valued goalkeepers during the 2022/2023 season. This shows that the most expensive goalkeepers are the best choice because usually the more expensive goalkeepers, the better the team is. For example, Ederson Moraes which is valued at 5.4 is not present in the above chart because Manchester City have such a brilliant defence and they do not concede a lot shots.</p>

<div align = "center">
  <img src = "https://github.com/ewaldo19/FPL-22-23-Data-Analysis/blob/cc166628321e4b53122127290b88cb064338df2d/data/Valued%20Goalkeepers.png">
</div>

<h3>Defenders</h3>
<img width="1000" alt="image" src="https://github.com/ewaldo19/FPL-22-23-Data-Analysis/assets/57058557/a047d5e0-f912-4380-9637-2862e0621124">
<p align = "justify">
The chart above showcases the Defenders with the highest value in the 2022/23 season. Kieran Trippier, contributing 11 assists for Newcastle United, demonstrates his significance for FPL players by meeting expectations. A notable inclusion in the chart is Castagne, despite Leicester's relegation following a disappointing season. Priced at just 4.3, he presents excellent value and stands out as an economical choice for FPL enthusiasts.</p>

<div align = "center">
  <img src = "https://github.com/ewaldo19/FPL-22-23-Data-Analysis/blob/f5520016f2f39941774771b19f21fc543ff043a6/data/Valued%20Defenders.png">
</div>

<h3>Midfielders</h3>
<img width="1000" alt="image" src="https://github.com/ewaldo19/FPL-22-23-Data-Analysis/assets/57058557/7315e007-8805-4c13-a844-b22f29770071">
<p align = "justify">The above chart shows the top 10 most valued midfielders throughout the season. Arsenal's stellar season did not went unnotice since their midfielders occupy the top 3 spots. Xhaka's 7 goals this season is his most prolific season of his Arsenal career. No one predicted that the former Arsenal skipper could provide this many point contribution as he was not a goalscoring midfielder. Almiron's fiery start to the season brought FPL players to their knees as he scored 9 goals in his first 19 matches to the season. Unfortunately, he only ended up with 11 goals so he only added 2 more goals to his tally for the rest of the season.</p>

<div align = "center">
  <img src = "https://github.com/ewaldo19/FPL-22-23-Data-Analysis/blob/81434cd64fe8da208f3a720797d54c4551f4e9d4/data/Valued%20Midfielders.png">
</div>

<h3>Forwards</h3>
<img width="761" alt="image" src="https://github.com/ewaldo19/FPL-22-23-Data-Analysis/assets/57058557/b0ddaa7a-f68d-43a6-8c41-6a77efb7c43d">
<p align = "justify">The above graph depicts the forwards with the highest value in the 2022/2023 season. The striking duo from Brentford, Ivan Toney and Bryan Mbeumo, emerge as a formidable pair, showcasing their ability to provide significant attacking contributions. Given that approximately 78.2% of FPL players have Erling Haaland on their teams, these players serve as an ideal complement to partner with him.</p>

<div align = "center">
  <img src = "https://github.com/ewaldo19/FPL-22-23-Data-Analysis/blob/f312180b545149fb3a57e57843f2df00ed567159/data/Valued%20Forwards.png">
</div>

