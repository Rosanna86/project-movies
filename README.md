# Project Movies

This project was made by Karoline Mann and Rosanna Dahlberg during week 12 of Technigos 24 week bootcamp.

The goal for this week was to use themoviedb.org's API to fetch a list of movies, display them on a page and then link to a movie detail page when you click on the movie. And also practice how to use React router to create multi-page applications and combining useState with useEffect.

## The problem

We began to make two components, one for the PopoularList with movies and one named Details with movie details. In our PopularList component we fetch the API with movies playing now. In Details we fetched the movie description and rating. We added a back-button with useHistory and a 404 error page.
Using the same logic as in the PopularList we then added more components fetching API's to display different types of movie themes - Top rated, Christmas and Halloween. 
All components were then structured with route paths in App.js. After we got all movie components to work we made a MovieBox component were we render each list box - so we don't have to go in on 4 different components to make changes. 

Both of us really enjoyed building this website and seeing how everything we've learnt, this far, about React came together in this project.


## View it live

https://the-movie-pop-corner.netlify.app/

