# ScottMorrisonMP-COVID-tweet-analysis
Analysis of @ScottMorrisonMP's COVID congratulations tweet (Tweet ID: 1322793255021420545)

Australian PM Scott Morrison made a congratulatory tweet about COVID-19 infections rates hitting zero in Australia. A few folks asked me to do some analysis of the replies and likes, as they suspected inauthentic activity around this tweet (which you can view here: https://twitter.com/ScottMorrisonMP/status/1322793255021420545).

This repository contains Python code to reproduce analysis of the 'likes' and sentiment of replies for this tweet.

You will find:

- Two text files with a manually copypasted list of 72 unique account names that liked the tweet (sorry, that's the maximum I could get because Twitter doesn't provide this data). I literally copied this from my browser by hand into a text file, and this was the limit. 

- Two text files with results of botometer bot analysis of the 72 accounts.

- A 'jsonl' format json file containing 806 replies to this tweet, collected using the 'twarc' Python module. Unfortunately, even though there is currently 3.3k replies, the collector hit an error due to a tweet being deleted during the collection process. Someone else might be able to complete the job.

- A Jupyter Notebook file with all the code for data collection and analysis.
