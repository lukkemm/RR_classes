Title :
Fifa19 Overall rank model improvement

Main Idea:
To create a model that can predict the overall rank of a Fifa19 player based on the ratings of his other skills and age.  This was done by me in our machine learning class where I created 3 different models to compare their accuracy.  One of them was a linear regression using OLS.  For this project we took that model and improved it by removing statistically insignifiant variables, performing variable transformations and running diagnostic tests.  In the end we came up with a slightly better model in terms of accuracy to predict the overall rank of a player.  Some of the variables had to be removed due to collinearity.  We also transformed the dependent variable (overall rank) to the logarithm of overall rank.

Dataset:
Ratings of players' skills from the video game Fifa19.  There is the overall rank as well as skills 
such as strength, speed, agility, etc.  There are 18,206 observations where each observation is a different player.  
There is a total of 31 variables (including overall and age).

Report structure:
We go over the model which was already created in my other class, then we describe how we attempted to improve it and present the final results.

I am working on the project with Sebastian Kremer.




