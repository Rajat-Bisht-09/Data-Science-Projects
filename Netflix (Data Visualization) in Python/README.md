
# Netflix Data Visualization using Python

Netflix is a global streaming service that offers a vast library of movies, TV shows, documentaries, and original content across various genres and languages. Launched in 1997 as a DVD rental service, Netflix transformed into an online streaming platform in 2007, revolutionizing the way people consume entertainment. It operates in over 190 countries, offering both licensed content and its own award-winning Netflix Originals. With a subscription model, users can stream content on-demand across multiple devices, including smartphones, tablets, computers, and smart TVs.

## Problem Statement

This tabular dataset consists of listings of all the movies and tv shows available on Netflix, along with details such as - cast, directors, ratings, release year, duration, etc. Analyze the data and generate insights that could help Netflix ijn deciding which type of shows/movies to produce and how they can grow the business in different countries.

### Dataset Description

| Variable	| Description |
|-----------|-------------|
| `show_id`	   | Unique identifier for each show or movie on Netflix |
|`type`  	   | either Movie or TV Show |
|`title`       | Title of the show or movie|
|`director`    | Director of the show or movie (if available)|
|`cast`        |Main cast of the show or movie|
|`country`     |Country where the show or movie was produced|
|`date_added`  |Date when the show or movie was added to Netflix|
|`release_year`|Year the show or movie was originally released|
|`rating`      |Content rating (e.g., PG, TV-MA)|
|`duration`    |Duration of the content (minutes for movies, number of seasons for TV shows)|
|`listed_in`   |Categories or genres the show or movie belongs to |
|`description` |Brief description or synopsis of the show or movie|

### Questions

- What is the distribution of content types (Movies vs. TV Shows)?
- What is the trend of content added to Netflix over the years?
- Which countries produce the most content on Netflix?
- How does the distribution of content vary by rating?
- What is the most frequent content duration for movies and TV shows?
- Which directors have the highest number of shows or movies on Netflix?
- What are the most common genres on Netflix?
- What is the distribution of content release years for Netflix shows and movies?
- Which actors or actresses appear the most in Netflix content?
- How does the type of content vary by genre?
- Is there a pattern in the release year of content across different genres?
- The best month to release the Tv-show
- The best month to release the Movie

### Insights and Recommendations

- **Insights**

  1. The content of Movies Vs TV Shows in Netflix Platform is more. The count of movies totals 6126 in number and TV Shows of 2664 in number. Also the movie contributes upto 69.7% and TV shows upto 30.3%.<br>
  2. Thecontent of Netflix started growing from 2015, and has been rising since then, but there is some downfall in recent years.<br>
  3. United States tops the chart in producing most content in Netflix with 3680 movies and TV Shows, next is India, UK, Canada and so on.<br>
  4. The highest content in Netflix is `TV-MA` > `TV-14` > `TV-PG`.<br>
  5. The average duration of Movies is `110.0` minutes, and the highest count of movie minutes is `90.0` minutes.<br> And most of the TV Shows have only `1` season.
  6. `Rajiv Chilaka` has the most content in Netflix in terms of *Director* Category. With a total of 22 Movies and TV Shows altogether.<br>
  7. The most common genres of the Netflix are - 
  - `International Movies`
  - `Comedies`
  - `Documentaries`
  - `Romance`
  - `Dramas`
  8. The content in Netflix shoots ups in the years between 2019-2020.
  9. `Anupam Kher` is the most successful actor in the Netflix, having total tally of 39 Movies so far.
  10. The month to release TV Shows are `July` and `December`.
  11. The month to release Movies are `January` and `July`.
