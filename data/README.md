# OSRS League data
A collection of ranking and player data for past leagues for analysis and historical purposes.


### League data files
* LeagueRanking.txt points and rank for the tiers, the number of players considered "active" is the rank of the Bronze players
* LeagueRanking-[League name].png LeagueRanking.txt as image
* LeagueRanking.json json format of LeagueRanking.txt
* LeagueRankingData.txt A series of data the same as LeagueRanking.json, with the time of recording (in milliseconds since 1970-01-01)
* LeagueUsers-[League name].json name, points and rank of the League players that obtained at least the Bronze rank at the end of the league
* LeagueUsers-[League name]-full.json name, points and rank of the League players that obtained at least the Bronze rank at the end of the league, their highscore stats, and the raw highscore api output
	* Since this takes time to collect, it is possible for players to change their names or have their account banned between collecting the list of Bronze+ players and their highscore data. When this happens, the highscore data for those players will be missing.

### Twisted League
As this was the first league, not all data was collected for this League, and the time series data collection only started about halfway.


### Trailblazer League

Due to the highscores for this League having been overwritten by a DMM final hour beta test, data after the league ended was not collected. A number of other sources of partial data are used.

* tbl-ranks.json A dump of data for players tracked by Wiseoldman.net
* TBL_raw.xlsx - TBL_raw.csv data for top 5000 collected by Explorifice after the League ended. Also includes highscore data
* LeagueUsers-Trailblazer.json is a combined version of the two above.



