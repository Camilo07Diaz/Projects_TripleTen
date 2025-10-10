# Data-Driven Insights for a Book Review App: SQL Analytics Project

## Project Overview
This project showcases a comprehensive SQL-based data analysis performed on the dataset of a book review startup. The company operates in a growing digital reading market, and the analysis aims to uncover strategic insights about books, authors, publishers, user behavior, and content engagement. The database includes structured information on books, authors, publishers, user ratings, and written reviews — making it an ideal case for relational database querying and business intelligence.

The analysis is implemented in Python (Pandas + SQLAlchemy) to interact with a PostgreSQL database hosted on AWS, allowing for flexible and efficient query execution within a Jupyter Notebook environment.

## Objectives
- The core goals of this analysis include:

- Determining the number of books published after the year 2000.

- Calculating the number of user reviews and the average rating per book.

- Identifying the publisher with the most substantial publications (books with over 50 pages).

- Finding the author with the highest average book rating, considering only books with at least 50 ratings.

- Measuring user engagement by calculating the average number of text reviews written by users who rated more than 50 books.

## Key Insights
- 819 books have been published after January 1, 2000, showing a strong focus on modern literature.

- Books like “13 Little Blue Envelopes” achieved an average rating of 4.67, signaling high user satisfaction.

- Penguin Books leads in publishing substantial content, with 42 books exceeding 50 pages.

- J.K. Rowling/Mary GrandPré emerged as the top-rated author, with an average score of 4.28 across highly rated books.

- Users who rated more than 50 books wrote an average of 24.33 text reviews, indicating a deeply engaged reader base.

## Tools & Technologies

- SQL (PostgreSQL)
- Python
- pandas
- sqlalchemy
- Jupyter Notebook

## Repository Content 

sprint_14.ipynb : Main notebook with analysis, visualizations and conclusions. 

## Author

Camilo Diaz
[LinkedIn](https://www.linkedin.com/in/camiloacdiaz) 