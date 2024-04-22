# Book Recommendation System

This project is a book recommendation system developed using Python, HTML, Bootstrap, Pickle, NumPy, and Pandas.

## Overview

The book recommendation system employs collaborative filtering to suggest books to users based on their preferences and interactions with similar users.

## Collaborative Filtering

Collaborative filtering recommends items to users based on the preferences of similar users. It leverages patterns in user behavior to offer personalized suggestions.. For example:

![Example](https://github.com/XuefengHuang/spark-book-recommender-system/raw/master/images/example1.png)

Now, let's say a seventh user wants a recommendation, and they've already read Book A. We can use collaborative filtering to suggest books similar to those liked by users who also liked Book A. In this case, User 1 and User 2 have both rated Book A highly and have similar tastes to our seventh user. So, based on collaborative filtering, we might recommend books that these users also liked, such as Book B and Book E, to our seventh user.

## Sections

- **Home Page**: Displays a list of popular and highly rated books.
![Book Cover](https://i.imgur.com/CyIs6eR.png)
- **Recommendation**: Users can input a book name, and the system recommends similar books based on collaborative filtering.
![Recommendation](https://i.imgur.com/jbPu9KM.png)
- **Search Books**: Allows users to search for specific books.
![Search Books](https://i.imgur.com/lz83nRL.png)

- **Contact**: Provides a contact form for users to send messages.
![Contact](https://i.imgur.com/BqZUdOR.png)


## Dataset

The dataset used for this project is sourced from Kaggle and includes three files: Books.csv, Users.csv, and Ratings.csv. These files contain information about books, users, and their ratings, respectively.

## How to Use

1. Install the required dependencies listed in `requirements.txt`.
2. Run `app.py` to start the Flask server.
3. Access the application through the provided URL.
4. Navigate through the various sections: Home, Recommend, Search Books, and Contact.
