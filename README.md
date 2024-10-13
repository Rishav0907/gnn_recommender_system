# GNN Recommender System

## Overview
This project implements a Graph Neural Network (GNN) based recommender system using PyTorch and PyTorch Geometric. The system is designed to recommend movies to users based on their past interactions and ratings.

## Features
- **LightGCN and NGCF Models**: Implements two popular GNN architectures for collaborative filtering.
- **Data Processing**: Handles data loading, preprocessing, and negative sampling for training.
- **Metrics Calculation**: Computes recall and precision metrics to evaluate the model's performance.
- **Training Loop**: Includes a training loop with loss computation and optimization.

## Requirements
- Python 3.x
- PyTorch
- PyTorch Geometric
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- tqdm


## Dataset
The dataset used in this project is the MovieLens 100K dataset. You can download it from [MovieLens](https://grouplens.org/datasets/movielens/100k/).

## Usage
1. Load the dataset and preprocess it.
2. Initialize the recommender model (LightGCN or NGCF).
3. Train the model using the training data.
4. Evaluate the model using recall and precision metrics.
