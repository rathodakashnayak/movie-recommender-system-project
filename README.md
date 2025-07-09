# Movie Recommender System

This project is a simple content-based movie recommender system built with Python and pandas. It uses the [MovieLens dataset](https://grouplens.org/datasets/movielens/) (`movies.csv`, `ratings.csv`, and `tags.csv`) to recommend movies similar to a given title based on genres, user ratings, and tags.

## Features

- Loads and merges movie, ratings, and tags data.
- Cleans and preprocesses movie titles and genres.
- Creates a combined "tags" feature for each movie.
- Uses `CountVectorizer` and cosine similarity to find similar movies.
- Provides a `recommend()` function to suggest movies based on a search string.

## Usage

1. Clone this repository and place the `movies.csv`, `ratings.csv`, and `tags.csv` files in the project directory.
2. Open and run the notebook `movie reccomender.ipynb` in Jupyter or VS Code.
3. Use the `recommend('movie name')` function to get movie recommendations.

## Example

```python
recommend('batman')
recommend('pirates')
```

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn

Install dependencies with:

```bash
pip install pandas numpy scikit-learn
```

## Acknowledgements

- [MovieLens Dataset](https://grouplens.org/datasets/movielens/)

