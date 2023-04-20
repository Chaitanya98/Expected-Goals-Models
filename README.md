# Expected Goals Models using Machine Learning

![last commit](https://img.shields.io/github/last-commit/Chaitanya98/Expected_Goals_Models)
![repo size](https://img.shields.io/github/repo-size/Chaitanya98/Expected_Goals_Models)

![alt text](https://github.com/Chaitanya98/Expected_Goals_Models/blob/main/Images/xG%20Infographic.png?raw=True)

<br>

Ever since the revolution of data analytics and the success of *Sabermetrics* in baseball, many sports started adopting the use of data in hopes of getting better results. Football, being the largest sport in the world, also went down this same path and came up with many advanced metrics to help the sport. One such metric is Expected Goals (commonly known as xG). <br><br>


Like Al Pacino says, Football is a game of inches. Eventhough he's referring to American Football here, the same can be said about Association football but with higher emphasis.<br>
Micro actions like the point of contact the player makes with the ball when passing or shooting, the stretch the goalkeeper makes when trying to make a save, a goal-line clearance defender can play a major role in deciding the outcome of a 90 minute game. <br><br>

When compared to sports like Basketball, American Football and Cricket, scoring is a rare occurrence in football. On an average, a match produces a total of 2.5 goals. A single goal can sway the result of the game. <br>
Since luck and randomness play a role in the outcome of a game, evaluating the performance of players and teams becomes difficult. We can see the scoreline and assess which team won, but we do not know if the winning goal(s) are a result of good performance or a lucky shot.<br><br>

This is where metrics like xG come into play. xG measures the probability that a shot taken will be converted into a goal. xG measures the quality of each shot before the player shoots, taking into account many factors. Some of them are,

* The shot angle 
* The distance from goal
* Body Part the ball is being shot with (Foot, Head, Torso etc.)
* If the shot creation is from a pass, cross, through ball etc. 
* The position of the opposition defenders.

xG gives a good measure of the chance creation qualities of teams when attacking and chance conceding ability when defending. It is also a good measure of the finishing abilities & chance creation abilities of outfielders  and the shot-stopping abilities of the goal-keepers.

#

The primary objective of this project is two-fold:

1. To thoroughly analyze the available data and identify the key features that have a significant impact on the likelihood of a goal being scored.
2. To build machine learning models that can accurately predict the probability of a goal being scored based on the identified factors.

#

This repostiory contains,

1. A data folder which contains a `ShotsData` CSV file has approximately 300,000 datapoints and consists of all the shots taken by all the teams in Top 5 Football Leagues in Europe. It consists location of shots taken in form of X,Y coordinates, the type and situation of the shots and other useful features to calculate xG. This dataset taken is from a website known as Understat.
2. `xG Models` jupyter notebook.

#
