## Flixster Android App

### Description

Android application that calls a movie db API to display a list of current movies in theatres. The application has the following functionalities:



-  Displays a list of current movie posters with corresponding descriptions in a RecyclerView
-  Uses a placeholder for movie posters not yet fully loaded on the screen
-  Exposes details of movie (ratings using RatingBar, popularity, and synopsis) in a separate activity.
-  Uses a different landscape activity when phone is in landscape mode to better format the information
-  Uses shared element activity transitions between the poster and the YoutubePlayer to create a smoother user experience
-  Movie trailers for more popular movies (popularity greater than 150) play automatically
-  Allows video posts to be played in full-screen using the YouTubePlayerView.

### App Walkthough GIF


<img src="https://github.com/advaithrai/newFlixster/blob/master/newflixster.gif?raw=true" width=250><br>

### Notes

-Working on making trailer videos fullscreen immediately upon clicking the movie poster when in landscape mode

## Open-source libraries used
- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android
