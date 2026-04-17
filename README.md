# Investigation-of-Netflix-Movies

Performed exploratory data analysis on the netflix_data.csv data to understand more about movies from the 1990s decade and answer the following questions:
1. What was the most frequent movie duration in the 1990s?
2. How many short action movies were released in the 1990s?

Problem-solving approach: 

1. What was the most frequent movie duration in the 1990s?
   
   1.1 Filtering the data for movies released in the 1990s by :

      a. Subsetting the Data Frame "release_year";

      b. Filtering by Column Values for the movies in the years 1990 - 2000.

   1.2 Finding the most frequent movie duration by :
   
   a. Visualizing distribution of filtered movies_list with their duration using Matplotlib,
   
   b. Finding the most frequent movie duration from observing the distribution.

2. How many short action movies were released in the 1990s?

   2.1 Count the number of short action movies from the 1990s by :

   a. Subsetting the filtered movies_list by Column "genre", saving it as Action_movies_list;

   b. Iterating through the Action_movies_list with a for loop and counting the short action movies with an if-else statement where duration is less than 90 minutes.
   
       
