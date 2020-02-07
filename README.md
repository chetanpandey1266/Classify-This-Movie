# Classify This Movie
Competition on Kaggle by Cyberlabs

## Problem Statement

For movie lovers, the movie poster makes up the first impression about the movie contents and its genre.
Humans can grasp the cues like color, expressions on the faces of actors etc to quickly determine the genre (horror, comedy, animation etc) of a movie. Though it might seem simple, it involves millions of concurrent processes occurring in a less than a jiffy! If humans are able to inherently predict genre of a movie by a glance at its poster, can't we expect the same from a machine ?

It has been studied that the human brain tends to make intuitions based on the color characteristics, local texture based features and structural cues of posters. Hence, the posters possess some characteristics which could be utilized for genre classification

In this competition, your goal is to predict the genres of movies from their posters.

## Data

The codes to download the data is provided in the "classify-this-movie.py"

## File Descriptions
### train.csv
The files contains 14969 rows with 2 features - id , genres in each row

id - A unique key by which the corresponding image is identified. genres - The genre of the movie. There are 10 unique genre - Comedy, Documentary, Drama, Horror, Thriller, Action, Romance, Crime, Adventure, Sci-Fi.

### sample_submission.csv
A valid sample submission. This files contains 29996 rows with 2 features - id, genres in each row

id - A unique key by which the corresponding image is identified. genres - Here you have to place predicted genre of the movie.

You must accept the competition's rules to gain access to the competition data.

## Background

The main library used for this competition is fastai, which is completely build on pytorch and provide easy to understand and implement codes. 

