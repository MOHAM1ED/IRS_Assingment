# IRS_Assingment
Mohamed Ibrahim Fekry :::::::::::::::::::::: ID:A20000726
To help you with the GitHub README file, I'll create a basic template that explains the purpose of the project, setup instructions, and usage. I’ll review the content of the provided Jupyter notebook to include any specific details.


---

# Movie Recommendation System

This project demonstrates a movie recommendation system using collaborative filtering techniques (User-based and Item-based) with cosine similarity and Pearson correlation. The project fetches data from the TMDb API and builds recommendations based on ratings data.

## Features

- **Fetch Popular Movies**: Uses the TMDb API to gather information on popular movies.
- **Recommendation Models**: Implements User-based and Item-based collaborative filtering using cosine similarity and Pearson correlation.
- **Evaluation**: Provides RMSE evaluations to assess recommendation accuracy.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

   Or install packages individually if `requirements.txt` is not provided:
   ```bash
   pip install requests pandas scikit-learn numpy
   ```

## Usage

1. **Fetch Movie Data**: Run the notebook cells to retrieve popular movie data from the TMDb API. Update the API key if necessary.
2. **Run Recommendation Models**: Follow the notebook to apply User-based and Item-based collaborative filtering models and obtain recommendations.
3. **Evaluate Models**: View the RMSE scores to determine the model's accuracy. 

### Example Workflow

1. Fetch popular movies:
   ```python
   movies = fetch_popular_movies(api_key)
   ```
2. Apply collaborative filtering models:
   - Cosine Similarity (User-based)
   - Cosine Similarity (Item-based)
   - Pearson Correlation (User-based)
   - Pearson Correlation (Item-based)

3. **Best Performing Model**: Based on the RMSE scores, the item-based model with cosine similarity had the lowest RMSE of 1.28, making it the most accurate among the models tested.

## Requirements

- Python 3.x
- TMDb API Key (sign up at [TMDb](https://www.themoviedb.org/documentation/api) to obtain your API key)
- Packages: `requests`, `pandas`, `scikit-learn`, `numpy`

---
