# Book Recommendation System

This is a machine-learning project that aims to build a book recommendation system using collaborative filtering techniques. The system recommends books to users based on their past reading history and user similarity.

## Introduction

The goal of this project is to create a book recommendation system that can help users discover new books based on their reading history and preferences. The system uses collaborative filtering techniques, specifically user-based collaborative filtering, to recommend books to users. Collaborative filtering is a popular recommendation approach that leverages the collective behavior and preferences of users to make recommendations.

## Usage

The recommendation system takes as input the user's reading history, which consists of books that the user has read or liked in the past. Based on this reading history, the system recommends a list of books that the user might be interested in. Users can interact with the system through a simple command-line interface.

## Data

The dataset used in this project is obtained from Goodreads-books
, a popular book review and recommendation website. The dataset contains information about books, users, and ratings. It is available in CSV format and is preprocessed to remove any irrelevant information and handle missing values.

The dataset is not included in this repository due to its large size. However, you can download it from Goodreads dataset link(https://www.kaggle.com/datasets/jealousleopard/goodreadsbooks) and place it in the 'data/' directory of this project.

## Model

The recommendation system uses user-based collaborative filtering to make book recommendations. It computes similarity between users based on their reading history and recommends books that are liked by similar users. The system uses cosine similarity as the similarity metric and selects the top N most similar users for recommendation.

## Contributing

Contributions to this project are welcome! If you would like to contribute, please follow the usual GitHub workflow:

- Fork the repository.
- Create a new branch for your changes.
- Make your changes and commit them with descriptive commit messages.
- Push your changes to your forked repository.
- Create a pull request to the main repository.





