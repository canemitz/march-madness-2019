# March Madness 2019
## Using machine learning to predict game outcomes

### Description
Using game data since 2003, I trained a logistic regression model on the Four Factors (estimated field goal %, turnover rate, offensive rebound rate, and free throw rate) as well as the NCAA tournament seeding. I then made predictions for the tournament based on each team's average regular-season statistics.

Adding the seed for each team helped a lot with improving predictions between teams from different conferences, and adjusting the C parameter improved results overall a good bit as well (the mean increase of accuracy was 5 percentage points, and the max increase was 12 percentage points, for the 2014-2019 tournaments).

For 2019, my model correctly predicted the winner of 47 of the 67 games that were played (70.1%).

A bracket made from the predictions is shown below. As of the Sweet Sixteen, it had 14 of the 16 teams correct.
![Image](https://raw.githubusercontent.com/canemitz/march-madness-2019/master/bracket2019.png)
