# March Madness 🏀

**Project**

Alright, this project is for those of you who are sick of toying around with toy housing data.

Included is a bunch of data sourced, collated, and cleaned. Importantly, however, not everything is done. There's still an endless amount of feature engineering to do!

The data spans 2003 to 2017 and is compiled from [sports-reference.com](https://www.sports-reference.com/cbb/schools/virginia/2019-gamelogs.html). 

The data is spread across four files:

- `regular_season.csv` - gamelogs for every regular season game
- `teams.csv` - team_id, names, and **conferences** (an important feature)
- `march_madness.csv` - gamelogs for each NCAA tournament game
- `march_madness_seeds.csv` - entry seeds for each team (W, X, Y, Z indicate the region)

Using these four files (and a healthy dose of `pd.merge(a, b, how='left', on=['x, 'y']`), purpose is to design/spin up a model that is "half decent" at predicting the outcomes of the NCAA March Maddness Tournament.

