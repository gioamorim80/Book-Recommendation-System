# Book-Recommendation-System

The goal of this project is to create a recommendation system for books. I'm using the data from the website Goodreads, made available on Kaggle, which consists of approximately 6 million ratings for 10,000 books, done by 53,424 unique users. Besides the ratings data, we also have access to metadata on the books, books genre and other tags, and books marked "to read" by users.

We will build a Collaboration Filtering model using the surprise library, experimenting with neighborhood or memory-based model with a couple of different similarity metrics, as well as with a Matrix Factorization-based approach.

Finally, we have a function that will take input (book ratings) from a new user and offer up a n number of recommendations.
