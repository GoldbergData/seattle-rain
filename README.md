# Does it really rain a lot in Seattle?
This repository contains code analyzing Seattle's rain from 1948 to 2017. The data used can be found on [Kaggle](https://www.kaggle.com/rtatman/did-it-rain-in-seattle-19482017). I became interested in Seattle after [relocating](https://twitter.com/GoldbergData/status/1256743534620745729?s=20) to the Pacific Northwest. A blog post summarizing more details can be found [here](https://joshuagoldberg.name/post/seattle-rain/).

## Goal of analysis
- What frequency does it rain?
- How much actual rainfall occurs (measured in percipitation/inches)?
- Are there seasonal trends of rain?
- Can we predict whether it will rain on a given day with the available data?

## Libraries
- numpy
- pandas
- collections
- random
- matplotlib
- sklearn
- seaborn
- tabulate

## Files
- [seattleWeather_1948-2017.csv](https://github.com/GoldbergData/seattle-rain/blob/master/seattleWeather_1948-2017.csv):  data set used for analysis
- [seattle_rain.ipynb](https://github.com/GoldbergData/seattle-rain/blob/master/seattle_rain.ipynb): notebook contaning the exploration and analysis
- [national_rainfall.png](https://github.com/GoldbergData/seattle-rain/blob/master/national_rainfall.png): image used in analysis for national comparison
- [readme.md](https://github.com/GoldbergData/seattle-rain/blob/master/README.md): file providing overview of repository

## Summary of the results
- It does rain a lot in Seattle compared to the rest of the country. However, if we look at actual rainfall, [Seattle ranks](http://www.usa.com/rank/us--average-precipitation--state-rank.htm) in the middle of the pack. 
- The summers are dry and warm.
- The winter vary the least as the high/low temperature range is narrow.
- Finally, our analysis showed that one day lag precipitation and and temperature can help with making reasonably accurate predictions.

## Acknowledgements
- [Kaggle](https://kaggle.com/)
- [Stackoverflow](https://stackoverflow.com/)
