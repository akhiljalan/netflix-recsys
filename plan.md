# Plan 

A plan to hold ourselves accountable. 

We want to finish this project in 4 weeks, so we'll divide it into 4 phases. Each of these should last a week. 

## Phase 1: Data Exploration, Augmentation, Cleaning 

We will read and organize the data into whatever formats seem useful. 

We'll try to augment the data in some way if it helps - for example, by scraping IMDB pages or RottenTomatoes percentages for the movies. 

### Web Scraping 

We want to augment our dataset with information from other movie rating sites, such as IMDB or RottenTomatoes. Genre, rating, and even plot summaries would be useful features to have. 

### SQL Server 

We want to practice our SQL skills by implementing a SQL server of some kind. It's not clear whether this would be useful, but it would be good practice. 

### Pandas Dataframe 

We'll organize the data into Pandas dataframes. 

## Phase 2: Baseline modeling and exploration 

First, we'll try to build a baseline model to compare performance against. This should be fairly common-sense based and help us get our feet wet. 

Second, we'll do some exploratory analysis and try to create useful visualizations. 

## Phase 3: Model Selection and Analysis 

We'll pick the model(s) that we want to explore and then implement them. 

## Phase 4: Writeup

We'll write up the results in a main notebook, organize the repo, and publish blog posts to share our work. 


### Ideas

* kNN for users

* Once we have genres attached to each movie after scraping, if we don't have enough intersection between the k users we can infer more data using similar movies the person has already watched in that genre based on some sort of text analysis from rotten tomatoes. 
* Could potentially use a combination of the two, where we somehow combine the similar users and the similar movies, then with some sort of model that learns ideal weights to put on the similar movies within the genre and the similar movies the k closest users have watched, the model can predict a solid top 5, say, of movies to watch.
* Don't have to restrict to genre, but a recommender system that takes in a genre input would be a good start.
