## 🎬 IMDb Movie Database Analysis 🍿

This Python script demonstrates how to analyze an IMDb movie database using a combination of SQL queries and data manipulation with Pandas. The database used in this example is an SQLite database named 'movies.sqlite' containing information about movies, directors, and more.

### 🔑 Key Steps in the Analysis 📈

1. **Importing Libraries** 📚: The script begins by importing the necessary libraries. The `pyforest` library automatically imports commonly used data science libraries like NumPy, Pandas, Matplotlib, and Seaborn, while `sqlite3` is used to interact with SQLite databases.

2. **Establishing a Connection to the SQLite Database** 🗄️: The script establishes a connection to the 'movies.sqlite' database and creates a cursor for database interactions.

3. **Data Retrieval and DataFrame Creation** 📊: The script retrieves data from the 'movies' table and creates a Pandas DataFrame called 'movies' to work with the data. This DataFrame is used for subsequent analysis.

4. **Movie Titles and Taglines** 🎥: For movies without taglines, a default tagline of "No tagline available" is assigned. The results are stored in the 'movie_tagline_df' DataFrame.

5. **Analyzing Movie Revenues** 💰: Movies are categorized as "Blockbuster," "High-grossing," "Moderate-grossing," or "Low-grossing" based on revenue thresholds. The results are stored in 'movie_revenue_category_df'.

6. **Analyzing Movie Popularity** 🌟: Movies are categorized as "Super Popular," "Very Popular," "Popular," or "Average" based on popularity thresholds. The results are stored in 'movie_popularity_df'.

7. **Top Movies** 🏆: Selection of top-rated movies with budgets over $50,000,000 and vote averages above 7.5, stored in 'high_budget_high_rated_movies_df'.

8. **Keyword-based Movie Search** 🔍: Searching for movies with 'Science Fiction' in their title or overview, ordered by vote_average and vote_count. Results are stored in 'science_fiction_search_results_df'.

9. **Audience's Choice** 🎉: Selecting the best movies released between '2001-01-01' and '2012-12-12', ordered by vote count. Results are stored in 'date_range_search_results_df'.

10. **Box Office King** 🎥💰: Finding the highest-grossing movie of all time and displaying it in 'highest_revenue_movie_df'.

11. **Summing Up Success** 💲: Calculating the total revenue of all movies in the database.

12. **Top 10 Lists** 📊: Retrieving and displaying the top 10 movies based on different criteria, such as vote count, budget, popularity, and combined release date and vote average.

### 🎬 Director Analysis 🎥

This script also includes director-related analysis:

1. **Getting All Directors' Data** 🎥: Retrieves all data from the 'directors' table in the database.

2. **Directors with Empty Portfolio** 📽️: Finds directors with no associated movies in the 'movies' table.

3. **Sorting Directors by Name** 🧑‍🎬: Sorts directors by name in ascending order.

4. **Filtering Female Directors** 👩‍🎬: Retrieves female directors in the 'Directing' department.

5. **Retrieving Movie Directors and Their Films** 🎞️: Joins the 'movies' and 'directors' tables to show movie titles and their directors' names.

6. **Keyword-based Director Search** 🔍: Searches for directors with names containing the substring 'Steven'.

7. **Top Directors** 🏆: Lists top directors by total movie revenue, average movie revenue, number of movies directed, and average vote average.

8. **Merging Movies and Directors** 📽️: Enhances movie details by displaying movies directed by a specific director (e.g., 'Christopher Nolan').

9. **Displaying a YouTube Video** 📺: Embeds a YouTube video related to Christopher Nolan's work in cinema.

### 🚀 Usage 🛠️

You can use this script as a starting point for your IMDb movie database analysis. Simply clone the repository and run the script to perform various analyses on the database.

### 🛠️ Dependencies 📦

- Python (3.x recommended)
- pyforest
- SQLite3
- Pandas
- Matplotlib
- Seaborn

### 🔗 Dataset
[imdb-sqlite-dataset](https://www.kaggle.com/datasets/prathammalvia/imdb-sqlite-dataset)
### 👨‍💻 Author 📝

[AryaInGit](https://github.com/AryaInGit)

