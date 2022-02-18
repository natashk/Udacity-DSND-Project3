# Udacity Data Scientist Nanodegree

## Recommendations with IBM

### Description

For this project Udacity provided real data from the IBM Watson Studio platform. The data sets contain the information about articles on the IBM Watson Studio platform and users interactions with them. There are no any type of ratings for whether a user liked an article or not. There is only the information that a user has interacted with an article. The goal of the project is to build a recommendation system that would make recommendations to users about new articles they might like.  

The project is divided into the following tasks:

#### I. Exploratory Data Analysis

Data exploration with visualizations.

#### II. Rank Based Recommendations

Since there are no ratings for articles, we assume the articles with the most interactions are the most popular. These are then the articles we might recommend to users.

#### III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we look at users that are similar in terms of the items they have interacted with. That way we could recommend articles, viewed by similar users. This is a step in the right direction towards more personal recommendations for the users.

#### IV Matrix Factorization

Another way of building recommendations is a machine learning approach. Using Singular Value Decomposition from numpy on the user-item matrix we got an idea of how well we can predict new articles an individual might interact with.

### Project files

    - data
    |- articles_community.csv          # data set with articles info
    |- user-item-interactions.csv      # data set with user interactions with articles

    - README.md                        # project description
    - Recommendations_with_IBM.html    # Jupyter notebook saved as HTML
    - Recommendations_with_IBM.ipynb   # Jupyter notebook with the project
    - user_item_matrix.p               # pickle file, provided by Udacity, used in last part of the project

    Files for tests, provided by Udacity:  

    - project_tests.py
    - top_10.p
    - top_20.p
    - top_5.p
