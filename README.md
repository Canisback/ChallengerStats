# Python analysis material for League of Legends Challenger games in 3v3

This repo offers some resources to perform game data analysis for League of Legends.

Stats about games are already computed and directly available in some notebooks (TTstats_EUW, TTstats_NA) at the end of each.

Final data can be found in the csv files. The limit date for before/after is 01/08/2018 (Patch 8.15 release).
A comparison between the four stacks can be found in the notebook compareStats. The file comparison.png is the final comparison dataframed styled, as Github does not render pandas Style.

If you want to perform the computation youself, you can reuse these notebooks, assuming you have a python environment with [Jupyter Notebook](http://jupyter.org/), MongoDB and [pymongo](https://api.mongodb.com/python/current/), [pandas](https://pandas.pydata.org/) and [Pantheon](https://github.com/Canisback/pantheon)

Use the gatherChallengerGames notebook to gather the games raw data from the Riot Games API. You will need and API key to put in the appropriate field (in the first cell), and can change your mongodb parameters in the 4th cell.