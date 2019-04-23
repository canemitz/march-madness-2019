# March Madness 2019
## Using machine learning to predict men's college basketball game outcomes

### Description
Using game data since 2003, I trained a logistic regression model on the Four Factors (estimated field goal %, turnover rate, offensive rebound rate, and free throw rate) as well as the NCAA tournament seeding. I then made predictions for the tournament based on each team's average regular-season statistics.

Adding the seed for each team helped a lot with improving predictions between teams from different conferences, and adjusting the C parameter improved results overall a good bit as well (the mean increase of accuracy was 5 percentage points, and the max increase was 12 percentage points, for the 2014-2019 tournaments).

### Files
* four-factor-seeded-logreg.ipynb  
Jupyter notebook with all the data wrangling, model fitting, and predicting in it.

* final_2019  
Results for the 2019 men's tournament, manually entered by me. *(To do: automate the creation of this file.)*  

* bracket2019.png  
A filled-out bracket based on the model's predictions. Shown below.  

* mens-machine-learning-competition-2019/Stage2DataFiles  
Folder with all the data needed to run the notebook (aside from final_2019). These were provided by the Kaggle competition.  


### Results
For 2019, my model correctly predicted the winner of 47 of the 67 games that were played (70.1%). It had Gonzaga beating Virginia in the championship game.

A bracket made from the predictions is shown below. As of the Sweet Sixteen, it had 14 of the 16 teams correct (it had Kansas St instead of Oregon, and Kansas instead of Auburn).
![Image](https://raw.githubusercontent.com/canemitz/march-madness-2019/master/bracket2019.png)
