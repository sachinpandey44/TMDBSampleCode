# OMDB 􏰀iOS App


## Overview

 OMDB is a mobile app that allows the user to search for any movie title, view the list of search results and details of the selected movie. The app fetches the movies data from The Open Movie Database (OMDb) REST API at http://www.omdbapi.com/.  The app contains two screens with details below:
 
1. Movies List Screen:
a. Includes facility to search for a movie with title
b. A list of movies that is scrollable and when the user reach the end of the screen, it 
fetches the next set of results if there is any.
d. The movie list is fetched from the OMDb. 
e. Tapping on a movie takes the user to Movie Details screen
2. Movie Details Screen:
a. The movie details is fetched from OMDb.
b. The user should be able to navigate back to the Movies List screen

### Additional details
- The app uses Apple developer recommended approach to cache and fetch images from URL for optimized performance. 
- CollectionView prefetching is used for smoother background fetch of data to be displayed on upcoming cells as user scrolls. 
- Basic unit and UI test cases are provided. 
     
