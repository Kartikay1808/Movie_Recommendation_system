# Movie_Recommendation_system

**Recommendation System**:
                      Recommendation System is a filtration program whose prime goal is to predict the “rating” or “preference” of a user towards a domain-specific item or item. In our case, this domain-specific item is a movie, therefore the main focus of our recommendation system is to filter and predict only those movies which a user would prefer given some data about the user him or herself.
                      
**Our Recommend System based on content Filterring**

**Content-based Filtering**:
    This filtration strategy is based on the data provided about the items. The algorithm recommends products that are similar to the ones that a user has liked in the past. This similarity (generally cosine similarity) is computed from the data we have about the items as well as the user’s past preferences.
    For example, if a user likes movies such as ‘The Prestige’ then we can recommend him the movies of ‘Christian Bale’ or movies with the genre ‘Thriller’ or maybe even movies directed by ‘Christopher Nolan’.So what happens here the recommendation system checks the past preferences of the user and find the film “The Prestige”, then tries to find similar movies to that using the information available in the database such as the lead actors, the director, genre of the film, production house, etc and based on this information find movies similar to “The Prestige”.
    Disadvantages
        Different products do not get much exposure to the user.
        Businesses cannot be expanded as the user does not try different types of products.
 
 
 **Dataset:**
 Data is taken from Kaggle.
 ## Datsset link https://www.kaggle.com/tmdb/tmdb-movie-metadata
 
 **Streamlit**:
 A Streamlit web application for the recommendation of movies. When the user searches for a movie we will recommend
the top 5 similar movies using our movie recommendation system. We will be using an item-based collaborative filtering
algorithm for our purpose.

# Streamlit web page Demo:
![Screenshot (79)](https://user-images.githubusercontent.com/92773900/148548761-16acc944-f1d4-4527-b354-7a61cc905a57.png)



 
