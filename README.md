# Movies_ETL

# Please see the Movie_ETL_Analysis.pdf file for the complete analysis. 

## Description

Amazing Prime is an online streaming movie service. To improve profit margins, they are wanting to develop an algorithm which
will predict which low budget movies released will become popular among their customers – thereby enabling them to purchase
the streaming rights at a low cost – before the movie becomes popular.

In order to facilitate creation of the algorithm, they have decided to hold a hackathon and see if they can source the algorithm
from the data science community. In preparation for the hackathon they have pulled movie and rating data from 2 different sources: 

•	Wikipedia scrape for movies from 1990

•	Rating Data from the MovieLens website

In this module, we used the Extract, Transform, Load (ETL) process to take 3 datafiles (‘wikipedia.movies.json’, ‘movies_metadata.csv’,
‘ratings.csv’) and prepare them for Amazing Prime’s hackathon. The general ETL process is shown below. We stored our cleaned data in an
SQL database called ‘movie_data’ and within 2 tables called ‘movies’ and ‘ratings’. 

## Resources

Python 3.6 (Python 3 environment)

Python Libraries - json, pandas, re, numpy, sqlalchemy, psycopg2, config, time

PostgresQL 11

Data files as outlined above

GitHub Repository - Movies_ETL 
