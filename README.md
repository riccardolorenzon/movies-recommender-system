# Movies Recommender System 

## Instructions

### Get the Data
Download the latest dataset from the [MovieLens website](http://grouplens.org/datasets/movielens/)

### Create the Movies DataSet
Run `prefs=recommendations.loadMovieLens()`

### Get the user-based-recommendations for the User with ID 87
Run `recommendations.getRecommendations(p,'87')[0:30]`

### Create the item similarities DataSet 
Run `itemsim=recommendations.calculateSimilarItems(prefs,n=50)`

### Get the item-based-recommendations for the User with ID 87
Run `recommendations.getRecommendedItems(prefs,itemsim,'87')[0:30]`

