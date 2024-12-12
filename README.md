# Film Finder 

Ever get caught up with your significant other on the couch at night blindly searching the internet for a movie to watch together? Takes a while, right? Not anymore with Film Finder! It's a simple SPA that will recommend random movies by genre, and you can like or dislike a movie to get another suggestion. Enjoy! 

## APIs
This app was created by calling the Movie Database API - https://www.themoviedb.org/. You will need to create an account and get your own API key for this SPA to work. 
## Potential additions 
1. Checkout the displayMovie() function in helpers.js to use the DOM to rearrange the layout of information on the page. Try displaying different types of information like cast, or release date.
2. Create a way to store a user’s liked and disliked movies and display this list on the page.
3. Our API call inside of getMovies() returns many pages of results, but currently our program only randomizes results from the first page. To randomize our results even more, update getMovies() so that movies contains results from a random page instead of the first page.
