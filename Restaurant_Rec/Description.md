## Project Description

### Business Objective: 
Enhance user experience through personalized recommendations and collaborate with restaurants on Yelp



### Data & Tools: 
A subset of Yelp's businesses, reviews, and user data is used. All businesses range across 8 metropolitan areas in the USA and Canada. Total data is 5GB combined.
The main tool is Pyspark. 



### CF Recommender System: 
Two algorithms are built based on Pyspark ALS model. 
1. Recommender for users: recommends top 10 restaurants (name, categories, wordcloud of categories)
2. Recommender for restaurants: recommends top 10 users (user ID, past visits, wordcloud of restaurant categories user have been to)

### Applications:
1. Provide personalized recommendations for Yelp users
2. Help restaurants on yelp make informed marketing decisions based on top users’ profiles.
3. The model can be applied to other larger datasets in different industries. 
   




