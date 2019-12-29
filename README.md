## Flixster Android App

### Description

Android application that calls a movie db API to display a list of current movies in theatres. The application haas the following functionalities:



-  Displays a list of current movie posters with corresponding descriptions in a RecyclerView
-  Uses a placeholder for movie posters not yet fully loaded on the screen
-  Exposes details of movie (ratings using RatingBar, popularity, and synopsis) in a separate activity.
-  Uses a different landscape activity when phone is in landscape mode to better format the information
-  Uses shared element activity transitions between the poster and the YoutubePlayer to create a smoother user experience
-  Movie trailers for more popular movies (popularity greater than 150) play automatically
-  Allows video posts to be played in full-screen using the YouTubePlayerView.

### App Walkthough GIF


<img src="https://github.com/advaithrai/Flixster_second_part/blob/master/flixster%20pt%202.gif?raw=true" width=250><br>

### Notes

Describe any challenges encountered while building the app.

- Tried to make the youtube video player fullscreen when in landscape mode, but the program crashed
- Also had difficulty figuring out how to make the text overview in the main activity stop at the end of the layout to make the app look cleaner
-Attempted adding shared element transitions, but didn't know where to put intent code

## Open-source libraries used
- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android
