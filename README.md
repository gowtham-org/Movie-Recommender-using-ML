# Movie Recommender System

This repository contains a Python project that demonstrates how to build a basic **Movie Recommender System** using **pandas**, **scikit-learn**, and **cosine similarity**.
## Project Overview

The notebook implements a **Content-Based Recommender System** to suggest similar movies based on user preferences. It utilizes a movie dataset and employs cosine similarity on movie features (primarily **movie overviews**) to recommend relevant movies.

## Features

- Content-Based Movie Recommendations (using movie overviews)
- Cosine Similarity based matching
- Easy-to-understand code with clear explanations
- Scalable to ~45k movies

## Technologies Used

- Python 3.x
- pandas
- scikit-learn
- numpy

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/gowtham-org/Movie-Recommender-using-ML.git
cd Movie-Recommender-using-ML
```

### 2. Upload the necessary .csv files in your notebook home directory:
Use kaggle URL for downloading datasets: https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset/data?select=movies_metadata.csv
- movies_metadata.csv
- credits.csv
- keywords.csv
  
### 3. Create *requirements.txt* file using below:
```bash
pandas
scikit-learn
numpy
jupyter
```

### 4. Install Dependencies
Create a virtual environment (optional but recommended) and install dependencies:
```bash
pip install -r requirements.txt
```

### 5. Run the Notebook:
```bash
jupyter notebook Movies-Recommender.ipynb
```
## Dataset
The project uses the Movies Metadata dataset (included or publicly available). The dataset contains movie titles, overviews, genres, and other metadata to build content-based recommendations.

### How it Works
- Load the movie dataset using pandas.

- Preprocess the data by handling missing overviews.

- Compute TF-IDF vectors from movie overviews.

- Calculate cosine similarity between all movies.

- Recommend similar movies when a user selects a movie title.

### Example usage:
```bash
get_recommendations("The Dark Knight")
```

