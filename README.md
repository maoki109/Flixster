# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [ ] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthrough GIF

<img src="https://i.imgur.com/goYAXoo.gif" width=250><br>

### Notes
Formatting the poster image view with the Movie Grid cell made the spacing between posters in the collection view funky, but some tweaking around fixed it.

When Estimate Size was set to Automatic for the Collection View, it made the posters very tiny. Changing Estimate Size to None fixed that issue and posters were shown at a viewable size.

---

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [ ] (1pt) Run your app on a real device.

### App Walkthrough GIF

<img src="https://i.imgur.com/felRy3V.gif" width=250><br>

### Notes
When pulling README changes from GitHub, all my work on local files were erased and blank files were committed to GitHub. Fixed the problem by going to Source Control Navigator (on the left side of XCode) > click on "Stashed Changes" > right click initial commit file > Apply Stashed Changes...

Poster images didn't show up at first because of a typo I had in my url.
