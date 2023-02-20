# Udactiy_DataSc_P3
Udacity Data Science Project 3 - Recommendation Engines (IBM collaboration)

In the IBM Watson Studio, there is a large collaborative community ecosystem of articles, datasets, notebooks, and other A.I. and ML. assets. Users of the system interact with all of this. Within this scope, we created this recommendation system project to enhance the user experience and connect them with assets. This personalizes the experience for each user.


## Objectives of Project


In this project the objective is to analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles it is believed they will like. Here is an example of what the dashboard could look like displaying articles on the IBM Watson Platform.


## Recommended initial Setup & Installations

They are quite some libraries used across the project, all referenced in the requirements.txt file. For a step by step setup ou can follow those 4 steps:

Create a virtual environment python -m venv .venv

Set Execution Policy Settings (optional only if next step leads to error) Set-ExecutionPolicy Unrestricted -Scope Process or Set-ExecutionPolicy RemoteSigned

Activate venv ..venv\Scripts\activate

Install required librairies pip install -r requirements.txt pip freeze > requirements.txt (to update requirements file with all installed packages)

## How to run the project

The whole conent of the project is held in a single notebook: Recommendations_with_IBM.ipynb.

Also for a simple read through an html version of the notebook is available : Recommendations_with_IBM.html

## Files Descriptions

- Recommendations_with_IBM.ipynb : The main notebook
- Recommendations_with_IBM.html : A HTML easy to read version of the project tasks
- Data folder, with articles in articles_community.csv & users activities in user-item-interactions.csv

## High Level Project Steps

I. Exploratory Data Analysis

Before making recommendations of any kind, you will need to explore the data you are working with for the project. Dive in to see what you can find. There are some basic, required questions to be answered about the data you are working with throughout the rest of the notebook. Use this space to explore, before you dive into the details of your recommendation system in the later sections.

II. Rank Based Recommendations

To get started in building recommendations, you will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. You will implement this next.

IV. Content Based Recommendations (EXTRA - NOT REQUIRED)

Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using your NLP skills, you might come up with some extremely creative ways to develop a content based recommendation system. You are encouraged to complete a content based recommendation system, but not required to do so to complete this project.

V. Matrix Factorization

Finally, you will complete a machine learning approach to building recommendations. Using the user-item interactions, you will build out a matrix decomposition. Using your decomposition, you will get an idea of how well you can predict new articles an individual might interact with (spoiler alert - it isn't great). You will finally discuss which methods you might use moving forward, and how you might test how well your recommendations are working for engaging users.

## Licensing, Authors, Acknowledgements, etc.

I thank the data provider IBM Watson Platform for the availibility of its dataset and share of project ideas.

As for links & helps, here are non-exhaustive list of external resources used during this project:

https://sparkbyexamples.com/pandas/pandas-groupby-count-examples/?utm_content=cmp-true

https://matplotlib.org/stable/tutorials/introductory/pyplot.html

https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.duplicated.html

https://www.geeksforgeeks.org/display-the-pandas-dataframe-in-table-style/

https://builtin.com/data-science/pandas-pivot-tables

https://towardsdatascience.com/reshaping-a-dataframe-with-pandas-stack-and-unstack-925dc9ce1289

https://numpy.org/doc/stable/reference/generated/numpy.dot.html

https://realpython.com/sort-python-dictionary/

https://www.tutorialsteacher.com/articles/sort-dict-by-value-in-python

https://www.listendata.com/2019/07/how-to-filter-pandas-dataframe.html

https://stackoverflow.com/questions/3462143/get-difference-between-two-lists-with-unique-entries

https://www.educative.io/answers/what-is-the-difference-between-pythons-list-append-and-extend
