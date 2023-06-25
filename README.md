# IMDB-Movie-Analysis
The project "IMDB Movie Analysis" involves analyzing a dataset containing various columns of different IMDB movies. The objective of the project is to frame a problem related to the dataset and use data analysis skills to explore the data, derive insights, and create a data story. The project consists of several tasks, including data cleaning, identifying movies with the highest profit, finding the top 250 movies based on IMDb rating, determining the best directors, identifying popular genres, analyzing movies featuring specific actors, and observing the change in the number of voted users over decades.

Here is a breakdown of the tasks involved in the project:

1. Cleaning the data: This step involves performing data cleaning tasks such as dropping columns, removing null values, and addressing any inconsistencies or errors in the dataset.

2. Movies with highest profit: Creating a new column called "profit" by calculating the difference between the "gross" and "budget" columns. Sorting the dataset based on the "profit" column and plotting a chart to observe outliers.

3. Finding the movies with the highest profit: Identifying the movies that have the highest profit based on the calculated "profit" column.

4. Top 250: Creating a new column called "IMDb_Top_250" and selecting the top 250 movies with the highest IMDb rating. Ensuring that the "num_voted_users" column for these movies is greater than 25,000. Adding a "Rank" column to indicate the ranks of the corresponding films.

5. Extracting non-English movies from the IMDb Top 250: Identifying movies in the "IMDb_Top_250" column that are not in the English language and storing them in a new column named "Top_Foreign_Lang_Film."

6. Finding the best directors: Grouping the dataset by the "director_name" column and determining the top 10 directors with the highest mean IMDb score. In case of a tie in IMDb score, sorting the directors alphabetically.

7. Finding popular genres: Analyzing the dataset to identify the popular genres among the movies.

8. Creating actor-specific columns: Creating three new columns named "Meryl_Streep," "Leo_Caprio," and "Brad_Pitt," which contain movies where the actors "Meryl Streep," "Leonardo DiCaprio," and "Brad Pitt" are the lead actors. Using only the "actor_1_name" column for extraction. Appending the rows of these columns and storing them in a new column named "Combined."

9. Finding critic-favorite and audience-favorite actors: Grouping the "Combined" column by the "actor_1_name" column and calculating the mean of "num_critic_for_reviews" and "num_users_for_review" to identify actors with the highest mean values.

10. Observing the change in the number of voted users over decades: Creating a column called "decade" to represent the decade to which each movie belongs. Sorting the dataset based on the "decade" column, grouping it by decade, and finding the sum of users voted in each decade. Storing the results in a new data frame called "df_by_decade."

The project aims to provide a detailed report on the dataset, addressing the questions mentioned and following the steps outlined above to analyze the IMDB movie data and derive meaningful insights.
