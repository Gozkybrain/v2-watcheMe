# watchMe - Movie App

watchMe V2 is the second iteration of [watchMe Movie Streaming App](https://github.com/Gozkybrain/watchMe) built with ReactJS that allows users to search for movies, view popular movies, and get movie details. It leverages the power of [TheMovieDB API](https://www.themoviedb.org/) to handle endpoints and fetch movie data.

<!-- ![watchMe Preview](./src/assets/watchMe.png) -->

## Features

- Search for Movies by Title
- View Popular Movies
- View Top Rated Movies
- View Recently added Movies
- Get detailed information about a movie
- Watch movie trailer through the app (Note: Streaming functionality not implemented)

## Technologies Used

- React JS
- CSS
- Axios
- React Slick
- react-bootstrap
- Font Awesome

## Project Structure

The project structure is organized as follows:

- `src/`
  - `assets/` - Contains static assets like images
  - `components/`
    - `TopNav.js` - Renders the navigation links and app logo.
    - `SearchBar.js` - Provides the search result for the movie query.
    - `MovieDetails.js` - Displays detailed information about a movie (description, actors, watch button).
    - `MovieSlider.js` - Implements the infinite scroll functionality for popular movies.
    - `HomeCard.js` - Serves at the mobile bottom navigation system.
  - `App.js` - Entry point of the application
  - `index.js` - Renders the app into the DOM

## Roadmap

Here's a step-by-step guide to building the watchMe app:

1. **Project Setup**: Set up a new React project with the necessary dependencies like React, Axios, Framer Motion, and react-bootstrap.
2. **Create Necessary Components**: Create the required components, including Navigation, SearchBar, MovieCard, MovieDetails, InfiniteScroll, SearchResult, and VideoModal.
3. **API Integration for Search**: Implement API integration for the search functionality. Use the API to fetch movie data based on the user's search query.
4. **Fetch and Display Popular Movies**: Utilize the API to fetch the most popular movies. Display them using the InfiniteScroll component.
5. **Movie Detail**: Create a component to display detailed information about a movie when a user clicks on a movie thumbnail or title.
6. **Video Modal**: Implement the VideoModal component to display an embedded trailer video when a user clicks on the watch button in MovieDetails.
7. **Styling**: Style the components to achieve the desired UI/UX. Use CSS or a styling library like styled-components.
8. **Testing and Debugging**: Test the app thoroughly and fix any bugs or issues that arise during testing.
9. **Deployment**: Deploy the app to a hosting service such as Netlify or Heroku to make it accessible to others.


## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, send an email to [gozkybrain@gmail.com](http://mail.google.com/)


