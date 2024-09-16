# Movie-Guide-App

A dynamic, user-friendly web application that allows users to search for movies, view detailed information, and manage their favorite movies.

## Features

- **Search for Movies**: 
  - Users can search for movies by name, helping them quickly find the titles they are looking for.
  
- **Real-Time Movie Data**: 
  - The app integrates with The Movie Database (TMDb) API to fetch real-time movie data, including titles, posters, ratings, genres, and summaries.
  
- **Popular and Top-Rated Movies**: 
  - Browse through lists of popular and top-rated films, offering recommendations to users based on TMDb's updated data.
  
- **Detailed Movie Information**: 
  - View detailed information about each movie, including a description, genre, user ratings, release date, and movie poster.
  
- **Favorites Management**: 
  - Users can manage their favorite movies by adding or removing movies to a favorites list for quick access later.

## Technologies Used

- **HTML5**: Structure of the web application.
- **CSS3**: Styling for the application’s user interface and responsive design.
- **JavaScript (ES6+)**: Core functionality, handling API requests, and dynamically rendering content.
- **The Movie Database (TMDb) API**: Fetch real-time movie data for search results, popular, and top-rated movies.

## How to Use

1. Clone this repository:
    ```bash
    git clone https://github.com/YourUsername/Movie-Guide-App.git
    ```

2. Get your API key from [The Movie Database (TMDb)](https://www.themoviedb.org/).

3. Create a `.env` file in the root directory and add your TMDb API key:
    ```bash
    TMDB_API_KEY=your_api_key_here
    ```

4. Open the `index.html` file in your browser.

5. Start searching for your favorite movies and explore popular and top-rated films!

## Screenshots

![Movie Search](img1.png)
![Movie Details](img2.png)

## Future Enhancements

- **User Authentication**: Allow users to sign in and save their favorites to the cloud.
- **Personalized Recommendations**: Suggest movies based on user preferences.
- **Watchlist**: Create a watchlist to track movies users want to see later.

## License

This project is licensed under the MIT License.
