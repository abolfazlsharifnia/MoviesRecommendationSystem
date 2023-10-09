# MoviesRecommendationSystem

## Overview

This project, `MoviesSuggestion.ipynb`, implements a hybrid recommendation system that combines collaborative filtering and content-based filtering to recommend movies to users based on their past ratings and the movie genres.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/abolfazlsharifnia/MoviesRecommendationSystem.git

Open the MoviesSuggestion.ipynb notebook in a Jupyter Notebook or Google Colab environment.

Run the cells in the notebook, replacing the userId and title with the desired values.

Retrieve the recommendations displayed in the output of the last cell of the notebook.

## Usage

Load your movies and ratings datasets:

import pandas as pd

movies = pd.read_csv('movies.csv')
ratings = pd.read_csv('ratings.csv')

Define the user ID and the movie title:

userId = 5
title = 'Toy Story (1995)'

Open the MoviesSuggestion.ipynb notebook in a Jupyter Notebook or Google Colab environment.

Run the cells in the notebook, replacing the userId and title with the desired values.

Retrieve the recommendations displayed in the output of the last cell of the notebook.
