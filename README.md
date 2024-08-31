# Movie Recommendation System
![Python](https://img.shields.io/badge/Python-3.11.2-blue)  ![Static Badge](https://img.shields.io/badge/API-orange) ![Static Badge](https://img.shields.io/badge/Machine_Learning-purple) 

## Introduction
The Movie Recommendation System is a web-based application that uses collaborative filtering, content-based filtering, or a hybrid approach to suggest movies to users. It leverages machine learning algorithms to analyze user data and generate tailored recommendations, enhancing the user experience.

## Resources
The movie details, such as title, genre, runtime, rating, poster, and more, are retrieved through The Movie Database (TMDb) API, as documented [here](https://www.themoviedb.org/documentation/api). Using the IMDB ID of each movie obtained from this API, I performed web scraping on the IMDB website to gather user reviews. Sentiment analysis was then conducted on these reviews to assess user opinions.<br />
Dataset link - https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

## How to Get the API Key?
Create an account in https://www.themoviedb.org/, click on the API link from the left-hand sidebar in your account settings, and fill in all the details to apply for the API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your API sidebar once your request is approved.
