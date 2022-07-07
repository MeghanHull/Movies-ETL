# Movies-ETL
## Project Overview
As part of the Amazing Prime Hackathon, Britta has requested an automated pipeline in order to daily update data from Wikipedia, Kaggle and the MovieLens ratings. The code needs to perform an ETL (Extraction, Transformation, and Loading) of the new data to the existing PostgreSQL database ***movie_data***.\

## Resources
### Data Sources
1. [wikipedia_movies.json](Resources/wikipedia_movies.json)
3. [movies_metadata.csv](Resources/movies_metadata.csv)\
   ***Source:*** Extracted from Kaggle [archive.zip](https://www.kaggle.com/rounakbanik/the-movies-dataset/download) 
4. ratings.csv\
   ***Source:*** Extracted from Kaggle [archive.zip](https://www.kaggle.com/rounakbanik/the-movies-dataset/download)

### Software
| Software | Version |
| :--- | :---: |
| Python | 3.7 |
| Conda | 4.13.0 |
| Jupyter Notebook | 6.4.8 |
| PostgreSQL | 11.16 |
| pgAdmin 4 | 6.8 |

# Deliverables 
## 1: Write an ETL Function to Read Three Data Files
- [ETL_function_test.ipynb](ETL_function_test.ipynb)
## 2: Extract and Transform the Wikipedia Data
- [ETL_clean_wiki_movies.ipynb](ETL_clean_wiki_movies.ipynb) 
## 3: Extract and Transform the Kaggle Data
- [ETL_clean_kaggle_data.ipynb](ETL_clean_kaggle_data.ipynb)
## 4: Create the Movie Database
- [ETL_create_database.ipynb](ETL_create_database.ipynb)
- [movies_query.png](Resources/movies_query.png)
- [ratings_query.png](Resources/ratings_query.png)
