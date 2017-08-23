# MovieMania
Movie Search Database

First API key uses OMDbAPI.com
This pulls the movie information like genre, year, release date, rating, plot, duration, actors,etc
  -Using this API allows the user to search movie and get generic information on it.
  - Add to calandar option given by Alexa: Will add the title, date it comes out (which is what calandar will use to add to calandar).
   
Second API key uses themoviedb.org
This pulls featured movies in theaters, coming soon, and recommendations based off what the users previous searches/likes/favorites were. This is connected to there account or make it so ALexa marks this personally and stores it in heer database.
  -Use SessionID for DynamoDB: so each user has a unique key and can go back into their spacific account for movies.
  
Third API key uses Guidebox
This API gives you streaming availability lists and prices

Fourth API key uses TuneFind
This lets you seatch movies/series to listen to music played.

Fifth API key uses TVmaze.com
This allows you to list tv/movie schedule listings on tv, can add to watchlist
  -Currently unavailable for commercial use.
