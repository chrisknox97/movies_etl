# ETL- Extract, Transform, Load

## Overview of Analysis

### Deliverable 1: To refactor code and write a new function that will read data from three sources (``wikipedia-movies.json``, ``movies_ metadata.csv``, ``ratings.csv``) and create three seperate Pandas DataFrames for each dataset. 

### Deliverable 2: To merge Wikipedia data with Kaggle metadata while extracting ``IMDB IDs`` with regular expressions and using a ``try-except`` block to register and note potential errors. 

### Deliverable 3: To extract and refactor Kaggle metadata and Movies Lens rating data into seperate seperate DataFrames. Then merge the Kaggle metadata with the Wikipedia movie dataframe to create the the ``movies_df``, before finally combining said ``movies_df`` with Movies Lens data to create ``movies_wth_ratings_df``.

### Deliverable 4: To import ``movies_df`` and ``ratings.csv`` into a SQL Database. 

## Results

### Deliverable 1

#### Completion of the first deliverable resulted in the creation of the three Pandas DataFrames shown below:

* Wiki Movies DataFrame

<img align="right" src="https://github.com/chrisknox97/movies_etl/blob/main/PNGS-%20Deliverable%201/wiki_movies_df.png" height="300">

* Kaggle Metadata DataFrame

![Deliverable1B](https://github.com/chrisknox97/movies_etl/blob/main/PNGS-%20Deliverable%201/kaggle_df.png)

* Movie Lens DataFrame

![Deliverable1C](https://github.com/chrisknox97/movies_etl/blob/main/PNGS-%20Deliverable%201/ratings_df.png)

The Python script written for this deliverable can be accessed [here](https://github.com/chrisknox97/movies_etl/blob/main/Deliverable%20One/ETL_Function_Test.ipynb).

### Deliverable 2

#### Completion of the second deliverable resulted in the Wiki movies DataFrame as well as a list of that DataFrame's columns, both of which are listed below:

* Wiki Movies DataFrame

![Deliverable2A](https://github.com/chrisknox97/movies_etl/blob/main/PNGS-%20Deliverable%202/wiki_movies_df.png)

* Wiki Movies DataFrame Columns List

![Deliverable2B](https://github.com/chrisknox97/movies_etl/blob/main/PNGS-%20Deliverable%202/wiki_movies_df_columns.png)

The Python script written for this deliverable can be accessed [here](https://github.com/chrisknox97/movies_etl/blob/main/Deliverable%20Two/ETL_Clean_Wiki_Movies.ipynb).

### Deliverable 3

#### Completion of the third deliverable created the ``movies_df`` and the ``movies_with_ratings_df`` as seen below:

* Movies with Ratings DataFrame

![Deliverable3A](https://github.com/chrisknox97/movies_etl/blob/main/PNGS-%20Deliverable%203/movies_with_ratings_df.png)

* Movies DataFrame

![Deliverable3B](https://github.com/chrisknox97/movies_etl/blob/main/PNGS-%20Deliverable%203/movies_df.png)

The Python script written for this deliverable can be accessed [here](https://github.com/chrisknox97/movies_etl/blob/main/Deliverable%20Three/ETL_Clean_Kaggle_Data.ipynb).

### Deliverable 4

#### The final deliverable for this module saw the addition of ``movies_df`` and ``ratings.csv`` into a SQL Database as demonstrated below; the result saw 6,052 and 26,024,289 rows added respectively. 

* Importing Rows from ``ratings.csv`` 

![Deliverable4A](https://github.com/chrisknox97/movies_etl/blob/main/PNGS-Deliverable%204/importing_rows.png)

* Movies DataFrame Row Count Query

![Deliverable4B](https://github.com/chrisknox97/movies_etl/blob/main/PNGS-Deliverable%204/row_count_movies.png)

* Movie Lens Ratings Row Count Query

![Deliverable4C](https://github.com/chrisknox97/movies_etl/blob/main/PNGS-Deliverable%204/row_count_ratings.png)

The Python script written for this deliverable can be accessed [here](https://github.com/chrisknox97/movies_etl/blob/main/Deliverable%20Four/ETL_Create_Database.ipynb).

## Summary

Extracting, Transforming, and Loading Data (ETL) is an important process to automate and update valueable information reguarly. 
