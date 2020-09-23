Project identifying what game factors determine the Best PGA wins and Top_10 finishes from 2010 to 2018
In this notebook, we're going to create a machine learning model that predicts which game factors on the PGA tour is most desirable for winning, utilizing criteria from Kaggle's PGA tour data.

1. Problem definition:
What are the most important game factors for PGA tour Wins and Top_10 finishes.

2. Data:
The data is downloaded from Kaggle: https://www.kaggle.com/jmpark746/pga-tour-data-2010-2018

3. Evaluation:
The evaluation metric will be determined by the model evaluating the best feature importances.

4. Features:
Kaggle provides a data list of 18 columns for data (see the link above)

Besides Wins and Top 10 finishes, the most important factors in winning are Average Score and Average SG Total
SG Total = Strokes Gained on average stokes of competitor.

Next step is to reformat the data to determine the "Best" from only the following categories:
Average Putts
Average Distance
Average Scrambling
gir(greens in regulation)
Fairway Percentage

According to the final model, gir(greens in regulation) are the most important feature when determining Wins and Top_10 finishes.
Followed closely by Average Putts. Surprisingly, Fairway percentage was rather low.
