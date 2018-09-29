# Python analysis material for League of Legends Challenger games in 3v3

This repo offers some resources to perform game data analysis for League of Legends.

Stats about games are already computed and directly available in some notebooks (TTstats, TTstats_NA) at the end of each.

If you want to perform the computation youself, you can reuse these notebooks, assuming you have a python environment with [Jupyter Notebook](http://jupyter.org/), MongoDB and [pymongo](https://api.mongodb.com/python/current/), [pandas](https://pandas.pydata.org/) and [Pantheon](https://github.com/Canisback/pantheon)

Use the gatherChallengerGames notebook to gather the games raw data from the Riot Games API. You will need and API key to put in the appropriate field (in the first cell), and can change your mongodb parameters in the 4th cell.