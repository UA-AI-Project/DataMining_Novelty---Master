# AI Project - Novelty

## Overview
This project focuses on studying and answering the following research question:

*When referring to users with variant gaming history, will novelty-optimized recommender systems recommend less popular items than baseline algorithms while maintaining relevance in the recommendations?*

In this project, there is an implementation of five different algorithms. Two of them are used as the baseline recommender systems, Item-KNN and User-KNN. The other three are extensions of the baseline algorithms and are used as the novelty-optimized recommender systems: Novelty-only Item-KNN, Novelty-only User-KNN, and Hybrid Novelty algorithm.

All the algorithms predict game recommendations for users, and based on the ground truth recommendations, their predictions are evaluated. This research focuses on novelty, relevance, and popularity metrics. The goal is to determine if, with the use of novelty-optimized algorithms, we can achieve more novelty, less popularity, and similar relevance compared to baseline algorithms.

The data used in this project come from the Steam platform and capture user interactions with the games available, showing which user has interacted with which games and how much they have played each game.

## Results
![Results](image.png)

The results show that the goal is achieved: novelty-optimized algorithms recommend games that are less popular and more relevant to the user's preferences than baseline algorithms by simply increasing the novelty.

## Sanity Checks
There are also some sanity checks to ensure that the recommendations are reproducible and do not contain duplicates.

## Run
To get these results, run the provided Jupyter notebook `novelty_notebook_Konstantina_Ellina.ipynb`. The notebook is organized into sections with Markdown cells explaining the entire procedure, including:

- Cleaning
- Filtering
- Algorithms Implementation
- Evaluation
- Sanity Checks
- Saving the Results
