# Analysis of the Movie Industry

## Project:

* Perform data analysis and create a presentation that explores what types of films are currently doing best at the box office.

## Dataset:

* IMDB

IMDB is one of the most credible sources out there for movie-ratings and popularity. This should provide us with enough quality data to perform our EDA and arrive at a conclusion for our project. 

## Objective:

1. Identify what genres have the the highest ratings in IMDB 
* Genre Analysis

2. Analyze each genre for its popularity and potential audience 
* Genre Outreach

3. Analyze the general trend in movie production
* Time-Series Analysis

## Assumption:

* The data received from IMDB is the most accurate representation of people's choice and preference in movies.
* All ratings received are unbiased when compared across different genres in terms of production quality, direction, actor's performance and region of debut.

## Process Overview:

1. Pre-Processing

* Create a master dataset by merging all provided datasets using a unique key.
* Drop any irrelevant columns.
* Remove or fill missing values.

2. Data Analysis

* Perform EDA with proper visualization to answer all objectives.

3. Conclusion

## EDA:

The master dataset is created by merging all six IMDB datasets. Missings values, irrelevant columns, and duplicates have been deleted accordingly to fit the purpose of the project.

1. Genre Analysis

For the first part of the project, we will need to get a total count of 'Average Rating' received for each genre. The one problem in this dataset is that some movies are tagged across multiple genres. Because the movie constitutes all genres that it was tagged,
it is safe to assume that each genre is a separate instance and that the average ratings received will be the same across each of the genres for the same movie.

The column with multiple genres are split into individual columns. Then, combined back into a single column creating different rows for each genre within a movie.

  

 






