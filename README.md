# Netflix-Prize-Recommendation-System

## Overview
This project aims to build a movie recommendation system using matrix factorization techniques. The dataset used is the MovieLens dataset, partitioned into training, validation, and test sets (33%, 33%, and 34%, respectively). The objective is to predict user ratings for movies with a focus on memory efficiency and achieving a low Root Mean Square Error (RMSE).

## Dataset
The MovieLens dataset is used in this project. It consists of user ratings for movies. The dataset is split into three parts:

Train Set: 33% of the data used for training the model.
Validation Set: 33% of the data used for tuning the model.
Test Set: 34% of the data used for evaluating the model's performance.

## Methodology
The project employs matrix factorization techniques to predict movie ratings. The key steps involved are:

1. Data Preprocessing: Cleaning and preparing the dataset for modeling.
2. Matrix Factorization: Implementing matrix factorization to factorize the user-movie rating matrix into user and movie latent factor matrices.
3. Model Training: Training the model on the training set.
4. Model Validation: Validating the model on the validation set to fine-tune hyperparameters.
5. Model Testing: Evaluating the model's performance on the test set using RMSE.

## Results
- Train RMSE: 0.81252
- Val RMSE: 0.91396
- Test RMSE: 0.92019

## Usage
To run the project, open the `movie_recommendations.ipynb` notebook and execute the cells in order. Ensure you have all the necessary libraries installed.

## Requirements
- Python 3.x
- Jupyter Notebook
- Libraries: NumPy, Pandas, Matplotlib, SciPy

## References
1. [MovieLens Dataset](https://grouplens.org/datasets/movielens/)
2. [Netflix Prize](https://www.cs.uic.edu/~liub/KDD-cup-2007/proceedings/The-Netflix-Prize-Bennett.pdf)
3. [BellKor Solution](https://www2.seas.gwu.edu/~simhaweb/champalg/cf/papers/KorenBellKor2009.pdf)
