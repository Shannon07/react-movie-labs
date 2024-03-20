# React-movie-labs & Assignment 1 - ReactJS app

Name: Shannon Garvey

## Overview.

This is a ReactJS app that displays movies by using the TMDB API.

### Features.
[ A bullet-point list of the __new features__ you added to the Movies Fan app (and any modifications to existing features) .]
 
+ Now playing page 
+ ~Popular page~
+ Top rated page
+ Trending page
+ Added production companies to movie details
+ Discover movies api is now sorted by popularity
+ Actors Page with a more info button to read more details about the actors (similar to the movies page)
+ Added new mui icon, 'whatshot' icon was added for the actors card
+ added new mui component - A Divider was added to the top of the movie details page and the actor details page

## Setup requirements.

Add .env file to the movies folder with the following code:

"REACT_APP_TMDB_KEY=... your API key value ...
FAST_REFRESH=false"

Replace 'your API value' with your tmdb api key from https://www.themoviedb.org

Starting the app:

In the terminal go to the movies folder and use:
'npm install'

followed by:
'npm start'

## API endpoints.

[ List the __additional__ TMDB endpoints used, giving the description and pathname for each one.] 

+ Must Watch movies - /movies/mustwatch
+ Now playing - Movies currently in theatres - /movies/nowplaying
+ Top rated movies - /movies/toprated
+ Trending movies - /movies/trending
+ ~Popular movies - /movies/popular~
+ Popular Actors - /actors/popular
+ Details for Actors - /actors/:id
+ 

## Routing.

[ List the __new routes__ supported by your app and state the associated page.]

+ /movies/mustwatch - (Must Watch Page) displays must watch movies that have been selected from the upcoming page.
+ /movies/nowplaying - (Now Playing Page) displays all movies currently playing in theatres.
+ /movies/toprated - (Top Rated Page) displays top rated movies from highest rated to lowest.
+ /movies/trending - (Trending Page) displays movies that are trending for that current day.
+ ~/movies/popular - (Popular Page) displays movies by popularity.~
+ /actors/popular - (Actors Page) displays actors sorted by popularity.
+ /actors/:id - (Actor Page) - displays details about the selected actor.

[If relevant, state what aspects of your app are protected (i.e. require authentication) and what is public.]

## Independent learning (If relevant).

Itemize the technologies/techniques you researched independently and adopted in your project, 
i.e. aspects not covered in the lectures/labs. Include the source code filenames that illustrate these 
(we do not require code excerpts) and provide references to the online resources that helped you (articles/blogs).
