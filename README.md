# Flixter
My First Ontraq Assignment

## Flix Part 1
Project setup: Completing this project requires the use of the AsyncHttpClient and the Glide libraries. You will need to add dependencies for these libraries to the app/build.gradle file.

### User Stories
A user story is a way to capture requirements for an app from an end-user perspective.
It is a common practice in app development and helps to simplify the way requirements are specified.

### REQUIRED (10pts)

- [x] (10pts) User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.

#### BONUS

- [x] (2 points) Views should be responsive for both landscape/portrait mode.
- [x] (1 to 5 points depending on the difficulty of UI improvements) Improve the user interface through styling and coloring.
  - [ ] (1 point) Display a nice default placeholder graphic for each image during loading (use the Glide library). If you’re running your app on an emulator, you can change the network speed of the emulator to test this feature by following the guidance here. 
  - [ ] (2 points) For popular movies (i.e. a movie voted for more than 5 stars), the full backdrop image is displayed. Otherwise, a poster image, the movie title, and overview is listed. Use “Heterogenous RecyclerViews” and use different ViewHolder layout files for popular movies and less popular ones. 

## Flix Part 2

### User Stories
A user story is a way to capture requirements for an app from an end-user perspective.
It is a common practice in app development and helps to simplify the way requirements are specified.

#### REQUIRED (10pts)

- [x] (8pts) Expose details of movie (ratings using RatingBar, popularity, and synopsis) in a separate activity.
- [x] (2pts) Allow video posts to be played in full-screen using the YouTubePlayerView.

#### BONUS

- [ ] Implement a shared element transition when user clicks into the details of a movie (1 point).
- [ ] Trailers for popular movies are played automatically when the movie is selected (1 point).
  - [ ] When clicking on a popular movie (i.e. a movie voted for more than 5 stars) the video should be played immediately.
  - [ ] Less popular videos rely on the detailed page should show an image preview that can initiate playing a YouTube video.
- [ ] Add a play icon overlay to popular movies to indicate that the movie can be played (1 point).
- [ ] Apply the popular ButterKnife annotation library to reduce view boilerplate. (1 point)
- [ ] Add a rounded corners for the images using the Glide transformations. (1 point)

### App Walkthough GIF

  <img src="https://i.imgur.com/oQ0AaRV.gif" title="App Walkthrough" />


## Open-source libraries used
- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android
