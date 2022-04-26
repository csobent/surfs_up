# Surfs_Up_Challenge
Tools: Jupyter Notebook, VS Code

## Overview of the Statistical Analysis:
The purpose of this module was to extract information about the precipitation and temperatures from the last 12 months using SQLAlchemy. We used August 23, 2017 as our reference point and subtracted 365 days using the datetime dependency. Once we were able to extract this data, we needed to target the months of June and December over the years to determine if the surf and ice cream shop business is sustainable year-round.

## Results
![June_stats.png](Images/June_stats.png) ![Dec_stats.png](Images/Dec_stats.png)

- When juxtaposing the June and December statistics, we can already see there is more data gathered for June than for December; a difference of 183 datapoints (1700 - 1517). 
- Since there is more data from June than from December, this affects the statistics given. We can especially see the affect on the average and minimum stats with an average temperature of 74.94 (June) and of 71.04 (Dec) and a minimum of 64 (June) and 56 (Dec). The max temperature was slightly affected with a two degree difference: 85 (June) and 83 (Dec).
- If we compare the quartiles between June and December, there is approximately a 3-4 degree difference between them: 25% (73 (June), 69 (December)), 50% (75 (June), 71 (December)), and 75% (77 (June), 74 (December)).


## Summary
![June_prcp.png](Images/June_prcp.png) ![Dec_prcp.png](Images/Dec_prcp.png)
