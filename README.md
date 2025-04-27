# Node.js-Express-with-PostgreSQL_Project

### Project description 

Create a RESTful API to provide data for a dashboard. Using your knowledge of Node.js, Express, and PostgreSQL, you’ll implement routes that fetch data from the database based on different requirements.

### The API Challenges 

Create the following API endpoints. Each endpoint should connect to the database, execute a query, and return the result as JSON.

##### Task 1: List All Players and Their Scores 

ENDPOINT: GET /PLAYERS-SCORES 

Description:
Write a route that uses an SQL query to list all players, the games they’ve played, and their scores. Include:

- Player’s name
- Game title
- Score

##### Task 2: Find High Scorers

ENDPOINT: GET /TOP-PLAYERS 

Description:
Write a route that returns the top 3 players with the highest total scores across all games. Sort them in descending order.

##### Task 3: Players Who Didn't Play Any Games

ENDPOINT: GET /INACTIVE-PLAYERS

Description:
Write a route that lists all players who haven’t played any games yet. 

##### Task 4: Find Popular Game Genres

ENDPOINT: GET /POPULAR-GENRES

Description:
Write a route that finds the most popular game genres based on the number of times they’ve been played. 

##### Task 5: Recently Joined Players

ENDPOINT: GET /RECENT-PLAYERS

Description:
Write a route that lists all players who joined in the last 30 days.

##### Bonus Task: Players' Favorite Games

ENDPOINT: GET /FAVORITE-GAMES

Description:
Write a route that returns each player’s favorite game (the game they’ve played the most).