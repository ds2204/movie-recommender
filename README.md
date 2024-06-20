# Movie Recommender System

Welcome to the Movie Recommender System! This application is built using Streamlit and leverages a pre-trained similarity model to recommend movies based on user selection. The app fetches movie posters using The Movie Database (TMDb) API to provide a visually appealing recommendation experience.

## Features

- **Interactive User Interface**: A clean and intuitive interface built with Streamlit, allowing users to select movies and get recommendations with ease.
- **Movie Recommendations**: Provides top 5 movie recommendations based on the similarity of the selected movie.
- **Movie Posters**: Fetches and displays movie posters using the TMDb API to enhance the user experience.
- **Feature Engineering**: Utilizes advanced feature engineering techniques, including text vectorization, cosine similarity, and stemming, to improve the accuracy and relevance of movie recommendations.

## Getting Started

## Prerequisites

 *Python 3.9 or higher
 *Streamlit
 *Pandas
 *Requests
 *Pickle

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/movie-recommender-system.git
   cd movie-recommender-system
2. Install the required packages:
   ```bash
   pip install streamlit pandas requests
3.Place your movie_dict.pkl and similarity.pkl files in the project directory.

## Running the Application
1. Run the Streamlit app::
   ```bash
   pip install streamlit pandas requests
   
## Usage

- Select a movie from the dropdown menu.
- Click the "Recommend" button to see the top 5 recommended movies along with their posters.
## Feature Engineering

Feature engineering is a crucial part of this project. It includes:

- **Data Cleaning**: Handling missing values, duplicates, and inconsistent data.
- **Feature Selection**:  Identifying and selecting the most relevant features for the recommendation model.
- **Feature Transformation**: Normalizing and transforming features to improve model performance.
- **Text Vectorization**: Converting text data into numerical vectors using techniques like TF-IDF.
- **Cosine Similarity**: Applying cosine similarity to measure the similarity between movie vectors.
- **Stemming**: Using stemming techniques to reduce words to their root forms for better text processing.

## API Reference

The application uses The Movie Database (TMDb) API to fetch movie posters.
You need to have an API key from TMDb to use this feature.

## Acknowledgements

-Streamlit
-Pandas
-Requests
-The Movie Database (TMDb)
![Screenshot 2024-06-20 224210](https://github.com/ds2204/movie-recommender/assets/108814222/2fbb0a91-53a1-4043-95a0-d2fc3c15e428)

