# Recommendation Systems
Each Notebook have a case for a recommendation system. 
This repo includes below python notebooks:
1. [Association Rule Learning Recommender (ARL Recommender)](https://github.com/hemekci/RecommendationSystems/blob/main/AssociatonRuleRecommender.ipynb)

The data set named Online Retail II is a UK-based online sale store's sales between 01/12/2009 - 09/12/2011 The product catalog of this company includes souvenirs. 

DATASET {InvoiceNo StockCode Description Quantity InvoiceDate UnitPrice (Sterling) CustomerID Country}

The goal is to apply association analysis to the online retail II dataset (in this case we will check Germany as an example) and suggest products.
Keywords: apriori , relational, basket, lift-support-confidence
    
2. [Hybrid Systems User-Based/Item-Based Recommender](https://github.com/hemekci/RecommendationSystems/blob/main/item_based_user_based_recommender.ipynb)

MovieLens Data https://grouplens.org/datasets/movielens/
Small: 100,000 ratings and 3,600 tag applications applied to 9,000 movies by 600 users. Last updated 9/2018.
movies.csv : movieId, title, genres, rating.csv : userId movieId rating timeStamp

We will find first the users-based recommeded 5 top movies after that 5 more recommendations will be given by item-based recommender depends on the user's last watched movies.
Key words: pearson correlation, hybrid, user-based, item-based, similar users, similar items
