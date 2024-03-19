# React-movie-labs & Assignment 1 - ReactJS app

Name: Shannon Garvey

## Overview.

This is a ReactJS app that displays movies by using the TMDB API.

### Features.
[ A bullet-point list of the __new features__ you added to the Movies Fan app (and any modifications to existing features) .]
 
+ Now playing page 
+ Popular page
+ Top rated page
+ Trending page
+ Added production companies to movie details
+ 

## Setup requirements.

Add .env file to the movies folder with the following code:

"REACT_APP_TMDB_KEY=... your API key value ...
FAST_REFRESH=false"

Replace 'your API value' with your tmdb api key from https://www.themoviedb.org

## API endpoints.

[ List the __additional__ TMDB endpoints used, giving the description and pathname for each one.] 

+ Must Watch movies - /movies/mustwatch
+ Now playing - Movies currently in theatres - /movies/nowplaying
+ Top rated movies - /movies/toprated
+ Trending movies - /movies/trending
+ Popular movies - /movies/popular

## Routing.

[ List the __new routes__ supported by your app and state the associated page.]

+ /movies/mustwatch - displays must watch movies that have been selected from the upcoming page.
+ /movies/nowplaying - displays all movies currently playing in theatres.
+ /movies/toprated - displays top rated movies from highest rated to lowest.
+ /movies/trending - displays movies that are trending for that current day.
+ /movies/popular - displays movies by popularity.

[If relevant, state what aspects of your app are protected (i.e. require authentication) and what is public.]

## Independent learning (If relevant).

Itemize the technologies/techniques you researched independently and adopted in your project, 
i.e. aspects not covered in the lectures/labs. Include the source code filenames that illustrate these 
(we do not require code excerpts) and provide references to the online resources that helped you (articles/blogs).
