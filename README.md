# meticritics_analyzer
Analyzing Movies Based on User's Reviews
Meticritics is one of those websites that is synomynous with movies ranking and reviews
If you want the best movie reccommedations and reviews, then Meticritics might be the answer

This project analyzes the movies not just based on their ranking by the users but also based on their genres and actors that played in them
The first thing that the project does is to scrap all the details of the top 500 movies in the meticritics website
After scrapping the details, the project saves them in a csv file with columns such as actors_List, movie name and even genre list.

When a user runs the script and searches for a specific actor, they should get the movies they acted on and the role they played in such movies
When a user, instead, searches for a specific movie, they should get the movie details including the actors and their roles as well as genre of such a movie
If the user, however, wants to compare between people, they can do so by entering names of the two actors they want to compare:
  The script will display the movies the actors have played in and the genres that they have engaged in
  Lastly, the script will display the cosine similarity of the two actors based on the provided information
