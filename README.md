# Recommendation-System-on-MovieLens-Dataset
## Project Overview: 
Knowledge-based, Content-based and Collaborative Recommender systems are built on MovieLens dataset with 100,000 movie ratings. These Recommender systems were built using Pandas operations and by fitting KNN, SVD & deep learning models which use NLP techniques and NN architecture to suggest movies for the users based on similar users and for queries specific to genre, user, movie, rating, popularity.

# Recommendation Systems : #

Recommender systems are the systems that are designed to recommend things to the user based on many different factors. These systems predict the most likely product that the users are most likely to purchase and are of interest to. Companies like Netflix, Amazon, etc. use recommender systems to help their users to identify the correct product or movies for them.

![1](https://user-images.githubusercontent.com/92712417/209871797-f707fa3c-6e49-42a1-9223-226f23fdcab9.png)

## Why use Recommendation System? ##

* enefits users in finding items of their interest
* help item providers in delivering their items to the right user
* identify products that are most relevant to users
* personalized content
* help websites to improve user engagement

# Types of Recommendation Systems : #

## 1. Popularity-Based Recommendation System ##
It is a type of recommendation system which works on the principle of popularity and or anything which is in trend. These systems check about the product or movie which are in trend or are most popular among the users and directly recommend those.
    
For example, if a product is often purchased by most people then the system will get to know that that product is most popular so for every new user who just signed it, the system will recommend that product to that user also and chances becomes high that the new user will also purchase that. 
    
    
    
## 2. Classification Model ##
The model that uses features of both products as well as users to predict whether a user will like a product or not. The output can be either 0 or 1. If the user likes it then 1 and vice-versa.
    
![8](https://user-images.githubusercontent.com/92712417/209872957-97b9095f-551f-46d8-91a8-860a555dd330.png)

## 3. Content-Based Recommendation System ##
It is another type of recommendation system which works on the principle of similar content. If a user is watching a movie, then the system will check about other movies of similar content or the same genre of the movie the user is watching. 
    
![3](https://user-images.githubusercontent.com/92712417/209873277-4f34c109-2ad8-41d9-a874-82d610b62c20.png)

formula for Euclidean distance :

![5](https://user-images.githubusercontent.com/92712417/209872740-42319627-a10f-4d81-b10e-ff9536ef1462.JPG)

Cosine Similarity :

![6](https://user-images.githubusercontent.com/92712417/209872742-d6d062c7-e8ab-45c6-af52-17ca392aa1ab.png)

Jaccard Similarity :

![7](https://user-images.githubusercontent.com/92712417/209872738-dc1c0392-5eba-44ef-b905-4d18aa5f4dbb.png)
    
## 4. Collaborative Filtering ##
It is considered to be one of the very smart recommender systems that work on the similarity between different users and also items that are widely used as an e-commerce website and also online movie websites. It checks about the taste of similar users and does recommendations.
    
![9](https://user-images.githubusercontent.com/92712417/209873178-25157790-c632-4e93-89be-bc4ab2f591f4.png)

![2](https://user-images.githubusercontent.com/92712417/209871803-35d3da18-8cde-412a-83fd-8b604a13e927.png)

![10](https://user-images.githubusercontent.com/92712417/209873377-b67fb4a5-5f93-496a-8761-2c6c89477982.png)

# About Dataset Used : #

MovieLens 100K dataset has been used for this project. MovieLens is a rating dataset from the MovieLens website, which has been collected over some period. Stable benchmark dataset. 100,000 ratings from 1000 users on 1700 movies. Released on 4/1998. MovieLens data sets were collected by the GroupLens Research Project at the University of Minnesota.

This data set consists of:

* 100,000 ratings (1-5) from 943 users on 1682 movies.
* each user has rated at least 20 movies.
* simple demographic info for the users (age, gender, occupation, zip)



