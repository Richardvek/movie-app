

# Movie App

## Description
The **Movie App** is a web application that enables users to search for and discover movies based on popularity and user input. The application utilizes The Movie Database (TMDb) API to fetch movie data and presents it in an engaging format.

## Features
- **Movie Discovery**: Browse popular movies sorted by their popularity.
- **Search Functionality**: Users can search for specific movies using a search bar.
- **Dynamic Movie Display**: Displays movie title, poster, average rating, and overview.
- **Responsive Design**: The app is designed for usability across various devices.

## Technologies Used
- **HTML**: For the structure of the web application.
- **CSS**: For styling and layout.
- **JavaScript**: For interactivity, including API calls and DOM manipulation.
- **The Movie Database (TMDb) API**: For accessing movie data.

## Getting Started
To run the Movie App locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Richardvek/movie-app.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd movie-app
   ```

3. **Open the `index.html` File**:
   Open the `index.html` file in your preferred web browser.

## Code Explanation
The core functionality of the Movie App is implemented in JavaScript, which fetches data from the TMDb API:

- **API URLs**:
  - `API_URL`: Fetches popular movies.
  - `SEARCH_API`: Used to search for movies based on user input.

- **Functionality**:
  - **Fetching Movies**: The `getMovies` function fetches movie data and calls `showMovies` to render the results.
  - **Displaying Movies**: The `showMovies` function creates movie cards that display the title, poster, rating, and overview of each movie.
  - **Rating Classes**: The `getClassByRate` function assigns color classes based on the movie's average rating.
  - **Search Feature**: The app listens for form submissions to trigger searches based on user input.

## Usage
- Start typing in the search bar at the top of the page.
- The app will display results based on the search input or show popular movies initially.

## Future Improvements
- Implement a feature to display more movie details when clicked.
- Allow users to save their favorite movies.
- Enhance the user interface with better styling and animations.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

