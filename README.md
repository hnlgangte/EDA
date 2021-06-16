# Exploratory Data Analysis on IMDb1000 movies dataset.

![dataset-cover](https://raw.githubusercontent.com/hnlgangte/EDA/master/images/dataset-cover.jpg "dataset-cover")

The purpose of the analysis is to find out the characteristics of movies that will help earn the best in terms of revenue, popularity and critical acclaim in the movie industry.
# Data overview
The dataset is taken from the** IMDB database.** It contains data of **1000** **most popular movies**(by IMDB rating) for the period **2006-2016.**

IMDB (Internet Movie Database) is an online database of information related to films, television programs, home videos and video games, and internet streams, including cast, production crew and personnel biographies, plot summaries, trivia, and fan reviews and ratings.

Users registered on this site are invited to rate any film on a scale of 1 to 10, and the totals are converted into a weighted mean-rating that is displayed beside each title.

Below is the data dictionary explaining the various columns of the dataset

| Columns | Description     |
|---------|-----------------|
|   Rank  | Movie rank order|
| Title   |The title of the film|
|Genre    | A comma-separated list of genres used to classify the film|
|Description|Brief one-sentence movie summary|
|Director   |The name of the film's director|
|Actors     |A comma-separated list of the main stars of the film|
|Year       |The year that the film released as an integer.|
|Runtime (Minutes)|The duration of the film in minutes.|
|Rating|User rating for the movie 0-10|
|Votes|Number of votes|
|Revenue (Millions) | Movie revenue in millions|
|Metascore|An aggregated average of critic scores. Values are between 0 and 100. Higher scores represent positive reviews.|

# Insights from analysis
## Industry Growth

- The movie Industry is growing in terms of the total number of movies released and the total revenue gained year on year.
- However, the average revenue of movies year on year is showing a negative trend. This is probably because of increased competition and more movies released in the industry.
- The popularity of movies is also showing a negative trend year on year. This is probably because of more movies released with Genre combinations which are unpopular among viewers.
## Genre

- The Revenue, Rating and Metascore of movies increases with the increase in Genre count.
- Movies with Genre count of 3 has a significantly high revenue.
- The Genre 'Adventure' is most common for movies which bring more revenue and "Animation, Drama, Fantasy" is the Genre combination with the highest Revenue.
- The most popular Genre is 'Drama' and the Genre combination "Animation, Drama, Fantasy" earns the highest Rating.
- The Genre 'Drama' is also highly popular among the critics as well.The Genre combination "Drama, Fantasy, War" has the highest Metascore.
- The Genre 'Fantasy' and 'Drama' is most common for movies with high Revenue, Rating and Metascore.
## Runtime

- Movies with Long runtimes (> 123 minutes) earn more in terms of Revenue, Rating and Metascore.
- Revenue is dramatically high for movies with Long runtimes.
## Director

- James Cameron is the director with the highest average Revenue. However he has directed only 1 movie in the 10 year period.
- Christopher Nolan's movies are the most popular among viewers as the average rating for his movies is the highest in the 10 year period.
- Barry Jenkins's movie has the highest Metascore. He too have directed only 1 movie in the 10 year period.
- Among the most active directors, J J Abrams's movies earn highest in terms of Average Revenue.
- Christopher Nolan is the most popular active director in terms of Average Rating among people.
- Among the most active directors, critics favor David Fincher in terms of Average Metascore.
## Rating of movies in General

- From the correlation graph, it is clear that People and Critics rate movies in a similar manner.
- In general, movies with higher rating and metascore tend to earn more revenue as well.

