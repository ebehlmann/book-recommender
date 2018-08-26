# Book recommendation engine using unsupervised learning on book rating data

## Udacity Machine Learning Engineer nanodegree capstone project

The goal of this project is to help readers find books to read next that are aligned with their tastes. Although readers' opinions about books are subjective, I will be able to measure how well readers like or dislike books based on the ratings they give them on a five-star scale. A good solution will be one that maximizes the rating score readers give to the books selected for them.

### Installation

This project is written in Python 3. It relies on the following libraries:

* Pandas
* Numpy
* Matplotlib
* Sklearn (specifically: TruncatedSVD, train_test_split, KMeans, silhouette_score and GaussianMixture)

Users may interact with the project by running the Jupyter Notebook book_recommendation_engine.ipynb. Juypter Notebook must be installed to run the notebook.

### Dataset

This project relies on the goodbooks-10k dataset, which was published under a Creative Commons license by Zygunt Zajac on the FastML website in 2017. The dataset, which can be found in the goodbooks-10k-data directory, includes about 6 million ratings of 10,000 books with the highest volume of ratings (ratings.csv). Each rating is associated with a user ID, making it possible to cluster individual readers based on their ratings. The dataset also includes metadata about each book, such as its title, author and average rating (books.csv).