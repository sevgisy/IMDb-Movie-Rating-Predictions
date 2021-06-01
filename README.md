# IMDb-Movie-Rating-Predictions
#datacleaning #ML
# INTRODUCTION
<img src="https://play-lh.googleusercontent.com/R5x56X7xOHZenDcDjP9q9qwWGg3iB7KKEz1KUMHbEurjDRXY4VLb3LBjOZ4u1_XiXzC-"     alt="Historical Temperature Change"     style="float: left; margin-right: 50px;width:300px;height:200px;" />

_IMDb (an acronym for Internet Movie Database)[¹](https://en.wikipedia.org/wiki/IMDb#cite_note-1) is an online database of information related to films, television programs, home videos, video games, and streaming content online – including cast, production crew and personal biographies, plot summaries, trivia, ratings, and fan and critical reviews. An additional fan feature, message boards, was abandoned in February 2017. Originally a fan-operated website, the database is now owned and operated by IMDb.com, Inc., a subsidiary of Amazon._

_As of December 2020, IMDb has approximately 7.5 million titles (including episodes) and 10.4 million personalities in its database,[²](https://en.wikipedia.org/wiki/IMDb#cite_note-stats-2) as well as 83 million registered users._

_IMDb began as a movie database on the Usenet group "rec.arts.movies" in 1990 and moved to the web in 1993._
[source](https://en.wikipedia.org/wiki/IMDb)


I intended to use a dataset consisting of IMDb information to create a
machine learning model which takes a movie’s features as input and predicts which potentially ratings. This tool would be useful for measuring the popularity of new films based on their features. Based on this aim, I determined our guiding questions and these are given below:

- Which features can be effective in the prediction of ratings?
- How is the relation between ratings and other features?
- How is the behaviour of top and bottom movies' features?

# CONTENT

1. [Gathering Data](#1)
    1. [Data Wrangling & Cleaning](#2)
        1. [Merging Tables](#2)
        1. [Limiting the Table](#2)
        1. [Adding Latitude and Longitude](#30)
        1. [Missing Values & Duplication](#31)
        1. [Cleaning Genres Column](#32)
        1. [Adding Top Actors and Directors Table](#33)
1. [Analysis](#3)
    1. [Exploratory Data Analysis](#3)
    1. [Mechine Learning](#5)
        1. [Random Forest Regression](#6)
        1. [Linear Regression](#7)
        1. [Generalized Linear Regression](#8)
        1. [Gradient-boosted tree Regression](#9)
1. [Conclusion](#10)
1. [References](#11)
   
