# netflix-movies-eda

# Project Overview

This project performs an Exploratory Data Analysis (EDA) on a dataset of Netflix movies to uncover trends in movie genres, ratings, and popularity. The analysis focuses on answering key business and entertainment questions through data visualization and statistical summaries.

# Problem Statement
The analysis aims to answer the following five questions:

Genre Frequency: What is the most frequent genre of movies released?

Top Ratings: Which movie has the highest average rating?

Maximum Popularity: Which movie reached the highest popularity and what is its genre?

Minimum Popularity: Which movie has the lowest popularity and what is its genre?

Peak Filming Year: In which year were the most movies filmed?

# Dataset Description
The analysis will be carried out using a dataset named Netflix_Movies.csv with 9,837 entries and 9 columns.

Key Columns: Release_Date, Title, Popularity, Vote_Average, Genre, and

Data Types: The dataset has a mix of numeric types (Popularity is a float64 data type) and categorical/text types (Title, Genre, Release_Date are objects).

# Data Cleaning & Preparation

Converted Release_Date to datetime and extracted release year

Handled missing values by dropping rows where required

Converted numeric columns using pd.to_numeric()

Used nullable integer type (Int64) for Vote_Count

Split multi-genre entries and expanded them using explode()

Removed duplicate records

Converted Genre to categorical type

# Key Findings

Most Frequent Genre: The most frequently occurring genre in the dataset is Drama.

Top Rated Movie: Kung Fu Master Huo Yuanjia is at the top with an average rating of 10.0, whereas Franco Escamilla: Por La Anécdota ranks second with 9.2

Most Popular: Spider-Man: No Way Home has the highest popularity rate and is categorized as an Action, Adventure, and Science Fiction movie.

Least Popular: The United States vs. Billie Holiday and Threads recorded the least popularity score of 13.354.

Most Productive Year: The year 2021 had the highest rate of filming in this dataset.

# Technologies Used
Python: The core programming language.

Pandas & NumPy: For data manipulation and numerical analysis.

Matplotlib & Seaborn: For data visualization.

Jupyter Notebook: The environment in which the analysis is performed.




