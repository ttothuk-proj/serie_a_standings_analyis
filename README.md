# serie_a_standings_analyis
Analysis of the last 15 years of Serie A's standings. Inspired by AC Milan's unbeaten run in the first 10 rounds of the 2020-21 season.
The data has been gathered from [WorldFootball](https://www.worldfootball.net/) using Python's BeautifulSoup library. The code for the scraping can be found under [webscraping.ipynb](https://github.com/ttothuk-proj/serie_a_standings_analyis/blob/main/webscraping.ipynb) and the resulting csv files are in [season_start.csv](https://github.com/ttothuk-proj/serie_a_standings_analyis/blob/main/season_start.csv) and [season_finish.csv](https://github.com/ttothuk-proj/serie_a_standings_analyis/blob/main/season_finish.csv).

The processed data helped to create the below attached barchart. It represents how the leaders changed after the 10th round in the Italian football league.  The bars over 0 represent the positions gained by a team, who finished 1st at the end of the season. For example, in the season 2017-2018 Juventus won the league, by stepping up 2 levels on the table.  The data under the 0-line shows teams that were leading the league after 10 rounds, however ended in a lower position by the end of season. In the same season, mentioned before Napoli was leading after Day 10, however they lost 1 position, hence finishing 2nd in the race for the Scudetto.


![](combined_half_titles.jpg)
