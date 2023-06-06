# [Movie DB analysis using Pandas](https://github.com/amido84/Movie_analysis/blob/main/Movie_analysis_using_pandas.ipynb)
Download movie lense dataset MovieLens and extract zip file using various python packages http://files.grouplens.org/datasets/movielens/ml-latest-small.zip

### [Movie DB Analysis Notebook](https://github.com/amido84/Movie_analysis/blob/main/Movie_analysis_using_pandas.ipynb)

### Sample:
1) Toy Story (1995),Adventure|Animation|Children|Comedy|Fantasy

2) Jumanji (1995),Adventure|Children|Fantasy

3) Grumpier Old Men (1995),Comedy|Romance

4) Waiting to Exhale (1995),Comedy|Drama|Romance

5) Father of the Bride Part II (1995),Comedy

6) Heat (1995),Action|Crime|Thriller

7) Sabrina (1995),Comedy|Romance

8) Tom and Huck (1995),Adventure|Children

9) Sudden Death (1995),Action


## List of Actions
1) Check if any of the columns are null.
2) Check datatype of each of the columns.
3) Using str on series genres, build following unique_genre set. It should contain all the unique genres from genres column. Print unique genres too.
4) Build columns for different genres with value True or False based on whether a genre is present or not in an observation.
5) Build a "year" column in movie data frame. The title "year" should be embedded in title columns.
6) Using seaborn, plot a bar plot of average number of movies per year.
7) Using matplotlib, plot total number of movies (cumulative over all the years) for each genre. Your plot should have proper title, axis labels and legends.
8) Build a movie_title column containing the title of the movie. (It should not contain year). Drop the original title columns. Display final movie dataFrame.
9) Using seaborn, plot average number of words in a movie name over the years in different genres. You may choose to make separate plots for each genre or to make a single color coded plot as a function of years. All plots should have proper title, axis labels and legends.

