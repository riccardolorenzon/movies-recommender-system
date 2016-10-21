# Movies Recommender System

## Instructions

### Get the Data
Download the latest dataset from the [MovieLens website](http://grouplens.org/datasets/movielens/)

### Open the Python shell
Run `python`
Within the Python shell, Run `import recommendations`

### Create the Movies DataSet
Within the Python shell, Run `prefs=recommendations.loadMovieLens()`

### Get the user-based-recommendations for the User with ID 87
Within the Python shell, Run `recommendations.getRecommendations(p,'87')[0:30]`

### Create the item similarities DataSet
Within the Python shell, Run `itemsim=recommendations.calculateSimilarItems(prefs,n=50)`

### Get the item-based-recommendations for the User with ID 87
Within the Python shell, Run `recommendations.getRecommendedItems(prefs,itemsim,'87')[0:30]`
