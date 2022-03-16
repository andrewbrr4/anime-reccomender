# anime-reccomender

This notebook plays around with a dataset of anime information, including data we use as features and the average rating of the anime. There are several non-text based features which we first process to create a XGBRegressor model to predict the expected rating of an anime. Then, we look at the synposes of the animes and created a tfidf matrix, which we then use to compute similarites between shows based on the synposes.
