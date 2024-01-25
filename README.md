# Baseball-2023
This is a short project on MLB players' hitting performances during the 2023 season. This was a take-home assignment for a data science job.

The csv file contains data from the recent MLB season. Each data point corresponds to a particular player's performance at a particular game. For each of these (48197 of them), we have the player's number of singles, doubles,	triples,	homeruns,	strikeouts,	walks,	hit by pitches,	field outs,	sacrifices, and	reached on errors.

There are a series of six open-ended questions to be answered in ~6 hours:

1. Which player had the longest hitting streak (consecutive games with at least one hit)?
2. Create a data visualization that shows the longest active hitting streak at any point in
time during the season.
3. Calculate every player’s longest hitting streak and batting average for the season. What
is the relationship between these 2 variables? What conclusions can be drawn from this
relationship?
4. Assume that a player receives exactly n at-bats per game in a 162-game season, and
that in each at-bat, he has a probability of p of getting a base hit. Then, build a function foo(n, p, x) that computes the probability of observing a hitting streak of at least x games for this player. Using this function with n = 4, determine the lowest value of p for which a 25-game hitting streak has at least a 20% probability of occurring.
5. Construct a system that groups similar players based on any metrics that you’d like to create (e.g. games played, batting average, on-base percentage, etc.). Are any of these groups more or less prone to longer hitting streaks?
6. Can you test whether streakiness (i.e., “hot hand”) is a real performance phenomenon, or whether we’re just seeing randomness? To do this, design and implement a generalized linear model (GLM) that learns the predictive impact of having a 3+ game hitting streak on getting a hit during the next game.

Using Logistic Regression (as well as SGD and Ridge Classifiers), I find that 'hot-hand' is not a real performance phenomenon. I conclude with some ideas on how to extend the project further with more time.
