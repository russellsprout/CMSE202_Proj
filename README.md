# CMSE202_Proj


This Repository contains the NBA_2.ipynb file.


Run the first 4 cells to webscrape the data into 2 data frames. One data frame will be the predictor data from the 19-20 and 20-21 seasons and the other will be the current data from the 21-22 season.


The next 3 cells will take the predictor data and simplify it so it only contains the statistics relevant to the project. It will also shwo you the correlation between these filtered statistics.


The next three cells will be used as visual representations for the presentation. The first is a heatmap of all the correlations and the second is a series of scatter plots showing correlation between certain statistics. The third is a histogram for the distribution of points scored.



The next two cells have three different ways of selecting predictors. The first is a normal multiple regression that shows correlation coefficients and p-values

The second is a forward selection of the best predictors and the third is a backwards elimination of the best predictors. Both of these are explained in more detail in the docstring for these cells


The next cells takes the predcitors from the backawarsd elimination and puts them into another linear regression. This is the final regression we will use the calculate our predicted scores.


The next cell contains a function that takes in the dataframe, the predictors from the regression, and the names of the two teams. Using the dataframe statistcs and the predictors coefficients, the function prints the predicted score of the two teams.


The final 3 cells take the current data from the 21-22 season and simplify it, just like we did for the 19-20 and 20-21 data. It then takes some games from this week and predicts the scores for them. The docstrings have the actual score  compared to the predicted score.
