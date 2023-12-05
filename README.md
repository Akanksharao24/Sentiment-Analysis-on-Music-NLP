# Sentiment Analysis of Lyrics

## Introduction

This project focuses on analyzing the sentiment of lyrics from various artists using Natural Language Processing (NLP) techniques. The sentiment analysis is performed using the VADER (Valence Aware Dictionary and sentiment Reasoner) sentiment analysis tool from the NLTK library. The goal is to understand the distribution of positive, negative, and neutral sentiments in the lyrics of different artists and to compare the sentiment percentages between selected artists.

## Code Structure

The code is organized into two main functions: `perform_sentiment_analysis` and `compare_sentiment_analysis`. Additionally, there is a section for reading datasets, user input, and a few utility functions.

### `perform_sentiment_analysis`

This function takes a DataFrame containing lyrics data for a specific artist and performs sentiment analysis on the lyrics using the VADER sentiment analyzer. The sentiment scores are then used to categorize the comments into positive, negative, and neutral sentiments. The results are displayed in both a pie chart and a bar graph for visual representation.

### `compare_sentiment_analysis`

This function compares the sentiment analysis results between two or more artists. It utilizes the `perform_sentiment_analysis` function for individual artists and then compares their sentiment percentages. The comparison results are displayed using bar graphs, providing a visual representation of the differences in sentiment distribution.

## Data and Artists

The project uses lyrics datasets for multiple artists, including Ariana Grande, Beyonce, Billie Eilish, Ed Sheeran, Justin Bieber, Katy Perry, Charlie Puth, Maroon 5, Post Malone, Rihanna, Selena Gomez, Coldplay, Drake, and Dua Lipa. These datasets are read from CSV files, and the lyrics data is processed for sentiment analysis.

## Usage

The user is prompted to choose between two options:
1. Analyze the sentiment of a single artist.
2. Compare the sentiment of two artists.

For option 1, the user selects an artist from the provided list, and the sentiment analysis results are displayed, including visual representations.

For option 2, the user selects two artists from the list, and the sentiment analysis results are compared and displayed in a bar graph. Additionally, the code provides a detailed comparison between the selected artists based on positive, negative, and neutral sentiment percentages.

## Visualizations

The project includes visualizations such as pie charts and bar graphs to better understand the distribution of sentiment in lyrics. These visualizations aim to provide a clear overview of the sentiments present in the lyrics of each artist and facilitate easy comparison between selected artists.

## Conclusion

This sentiment analysis project provides insights into the emotional tone of lyrics from various artists. The comparison feature allows users to explore and understand the differences in sentiment distribution between two selected artists. The code can be further extended to include more artists or additional features for a more comprehensive analysis.

The provided Python script, when run, enables users to interactively explore and compare sentiment analysis results for lyrics of different artists.
