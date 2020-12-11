# serie_a_standings_analyis
Analysis of the last 15 years of Serie A's standings. Inspired by AC Milan's unbeaten run in the first 10 rounds of the 2020-21 season.
The data has been gathered from [WorldFootball](https://www.worldfootball.net/) using Python's BeautifulSoup library. The code for the scraping can be found under [webscraping.ipynb](https://github.com/ttothuk-proj/serie_a_standings_analyis/blob/main/webscraping.ipynb) and the resulting csv files are in [season_start.csv](https://github.com/ttothuk-proj/serie_a_standings_analyis/blob/main/season_start.csv) and [season_finish.csv](https://github.com/ttothuk-proj/serie_a_standings_analyis/blob/main/season_finish.csv).

The processed data helped to create the below attached barchart. It represents how the leaders changed after the 10th round in the Italian football league. If there are no bars it means that whoever was leading after 10 rounds, won in the end. <br/> - The bars over 0 represent the positions gained by a team, who finished 1st at the end of the season. For example, in the season 2017-2018 Juventus won the league, by stepping up 2 levels on the table. <br/> - The data under the 0-line shows teams that were leading the league after 10 rounds, however ended in a lower position by the end of season. In the same season, mentioned before Napoli was leading after Day 10, however they lost 1 position, hence finishing 2nd in the race for the Scudetto.

Over the previous 15 seasons only 3 teams managed win the league after being in a lower position after Day 10. Inter once, AC Milan once and Juventus 3 times. Overall, teams tend to win the league if they are in the league with 28 games remaining. When a team had at least 26 points after 10 ronnd they won the league 5 out of 7 times. The biggest comeback belongs to Juventus's name, who went on to win the league in the 2015-2016 sesaon after being only in the 12th place after 10 games. The largest loss happened Lazio's 2010-2011 season, where - after a confident start - they finished 5th in the league.

Extra fun facts from the exploration of the dataset: 
- 40 teams played in Seria A in the last 15 years
  - 6 of them playing in all of them (AS Roma, Lazio, Fiorentina, Inter, AC Milan, Udinese)
- The team gaining the most positions in the last 28 rounds was AC Milan in the 2005-2006 season, where they climbed up 14 steps on the ladder, to finish 4th in the end (after they started the season on -30 points).
- Team losing the most positions in the last 28 rounds was Sampdoria who could not manage to get out of the relegation zone (finished 18th), after being 10th after 10 rounds.


![](/img/combined_half_titles.jpg)


Over the last 15 years this is AC Milan's best start, giving them a good chance to win the title this year.
![](/img/milan_starts.png)


Looking at the previous years and averaging the positions gained in last 28 rounds, Milan sits on top with around 3 position improved.
![](/img/average_position_change.png)
![](/img/total_position.png)
