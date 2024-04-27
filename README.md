# Intelligent-Recommendation-Engine-Combining-Collaborative-Filtering-and-Learning-to-Rank

This repository contains the implementation of an intelligent recommendation engine that leverages both collaborative filtering techniques and learning-to-rank algorithms. The project aims to build a robust and versatile system capable of providing personalized recommendations while ensuring optimal ranking and user satisfaction.

## Project Overview

The project is divided into two main sections:

1. **Collaborative Filtering**: This section focuses on implementing various collaborative filtering algorithms, including neighborhood-based and model-based approaches, to predict user ratings for unrated items. The techniques explored include:

   - User-based k-Nearest Neighbors (k-NN)
   - Non-negative Matrix Factorization (NMF)
   - Matrix Factorization with Bias (MF with Bias)

2. **Learning to Rank**: This section introduces the concept of learning to rank and demonstrates its application using the LightGBM library with the LambdaRank algorithm. The learning-to-rank approach is applied to the Microsoft Learning to Rank (MSLR-WEB10K) dataset, aiming to optimize the ranking of items based on their relevance to user queries or preferences.

## Key Features

- **Collaborative Filtering Algorithms**: Implement and evaluate various collaborative filtering techniques, including user-based k-NN, NMF, and MF with Bias, to predict user ratings for unrated items.
- **Cross-Validation**: Employ k-fold cross-validation to assess the performance of the collaborative filtering models on the dataset.
- **Dataset Analysis**: Explore and visualize the properties of the movie rating dataset, including sparsity, rating distributions, and variance analysis.
- **Interpretability**: Investigate the interpretability of the NMF model by examining the connection between latent factors and movie genres.
- **Learning to Rank**: Implement the LightGBM library with the LambdaRank algorithm to optimize the ranking of items based on their relevance to user queries or preferences.
- **Evaluation Metrics**: Utilize relevant evaluation metrics, such as Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and Normalized Discounted Cumulative Gain (nDCG), to assess the performance of the recommendation models.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository
2. Download the datasets (links provided in the project spec)
2. Run the Jupyter notebook

The notebooks are self-contained and provide detailed explanations of each step.

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Acknowledgments

I thank Professor Vwani Roychowdhury and the course staff of ECE 219 for their guidance on this project.
