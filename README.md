# Content-Based Restaurant Recommendation System

Project Overview

This project showcases a content-based recommendation system designed to suggest restaurants to users based on their preferences. Using a dataset of Bangalore restaurants from Zomato, the model leverages features like cuisine, location, and restaurant type to find and rank restaurants that are most similar to a user's choice.

The core of the project involves transforming textual and categorical data into a numerical format suitable for machine learning. This is achieved by combining various features into a unified "soup" of keywords for each restaurant. The similarity between restaurants is then calculated using the cosine similarity metric, allowing the system to provide accurate, content-driven recommendations.

Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn (for `TfidfVectorizer`, `cosine_similarity`)
- Matplotlib
- Seaborn

Dataset
The dataset for this project is `3B.tsv`, which contains detailed information about restaurants in Bangalore, including their names, cuisines, locations, ratings, and types.

How to Run this Project
1. Clone the repository to your local machine:
   ```bash
   git clone [https://github.com/geraldusjeremy/Restaurant-Recommendation-System.git](https://github.com/geraldusjeremy/Restaurant-Recommendation-System.git)

