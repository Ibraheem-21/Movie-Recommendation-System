# Movie Recommendation System

This repository contains the code and data needed to build a simple Movie Recommendation System using collaborative filtering and content-based filtering techniques. The system utilizes movie ratings and metadata to provide personalized movie recommendations based on user preferences and viewing history.

## Project Overview

The Movie Recommendation System is designed to help users discover movies they may enjoy by analyzing patterns in movie ratings and movie features. By combining collaborative filtering (user-item interactions) and content-based filtering (movie features), the system generates tailored recommendations that can be further enhanced with machine learning techniques.

### Project Files

- **`Movie_Recommendation_System.ipynb`**: The main Jupyter notebook that contains all the code for data loading, data preprocessing, model building, evaluation, and generating recommendations.

- **Data Files**: Two CSV files provide the core data needed for the recommendation system:
  - **`movies.csv`**: Contains details on various movies, including movie IDs, titles, and genres.
  - **`ratings.csv`**: Holds user ratings for different movies, featuring user IDs, movie IDs, and corresponding ratings.

### Data Access

The two CSV files can be accessed through this [link](https://tinyurl.com/MRSDataset).

### Requirements

To run the code in the notebook, you'll need the following Python packages installed:
- `pandas`
- `numpy`
- `scikit-learn`
- `scipy`

You can install these packages using:
```bash
pip install pandas numpy scikit-learn scipy
```

### Usage

1. **Load Data**: The data files (`movies.csv` and `ratings.csv`) are loaded and preprocessed in the Jupyter notebook.
2. **Data Preprocessing**: The data undergoes cleaning and formatting to remove duplicates, handle missing values, and format ratings.
3. **Model Building**: Two types of recommendation techniques are implemented in the notebook:
   - **Collaborative Filtering**: Based on user-item interactions.
   - **Content-Based Filtering**: Based on movie features like genres and keywords.
4. **Generate Recommendations**: Using the models, recommendations are generated for new or returning users based on their profiles and rating history.
