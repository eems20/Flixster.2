## Flix Part 2

### User Stories

#### REQUIRED (10pts)

- [X ] (8pts) Expose details of movie (ratings using RatingBar, popularity, and synopsis) in a separate activity.
- [ X] (2pts) Allow video posts to be played in full-screen using the YouTubePlayerView.

#### BONUS

- [ ] Trailers for popular movies are played automatically when the movie is selected (1 point).
  - [ ] When clicking on a popular movie (i.e. a movie voted for more than 5 stars) the video should be played immediately.
  - [ ] Less popular videos rely on the detailed page should show an image preview that can initiate playing a YouTube video.
- [ ] Add a play icon overlay to popular movies to indicate that the movie can be played (1 point).
- [ ] Apply the popular ButterKnife annotation library to reduce view boilerplate. (1 point)
- [ ] Add a rounded corners for the images using the Glide transformations. (1 point)

### App Walkthough GIF
<img src="flix2.gif" width=750><br>


### Notes

Difficulties was adding the API implementation, but I am able to better understand Android App development. This app only covers the basic stories
but development for bonus activites are in progress right now. I have an upcoming convention, so timing is limited for app development.

## Open-source libraries used
- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android
