## Feature Engineering

- commonly applied.
**Mainly worked by** https://github.com/msmsm104/ and https://github.com/HalfMoon1008


### Version 01
**feature engineering_1차(0607).ipynb**
  * Mainly get the code from **Kaggle** to reduce memory. 
  **Memory saving function credit to** https://www.kaggle.com/gemartin/load-data-reduce-memory-usage
  * Delete columns with objects : Id, groupId, matchId, matchType
  * Delete columns that have less connection or less correaltion with Target(winPlacePerc) : rankPoints, roadKills, matchDuration, teamKills

### Version 02
**Feature_engineering_2차(0610).ipynb**
  * Delete columns that have many missing values : killPoints, winPoints
  * Modify matchType from object(string) to categorical value
  * Compare columns : maxPlace, numGroups => These fatures are highly observed for VIF and correlartion. => Using numGroups by modifing categorical values.
  * Added codes from teammates that they worked for.

### Version 03
**feature_engineering_3차(0613)_1(dataFrame).ipynb**
  * Concatenating codes into one function(feature_engineering_to_df)
  * Combining two features into one(heals_boosts) => heal and boost are in area of buff. 

### Version 04
**feature engineering 4차(0613).ipynb**
  * Added function to show state
  * Modified function
