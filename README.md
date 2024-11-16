# restaurant-recommendation-system

## Overview
The Restaurant Recommendation System is designed to suggest similar restaurants based on user reviews. It leverages TF-IDF (Term Frequency-Inverse Document Frequency) and Cosine Similarity to analyze restaurant reviews and provide personalized recommendations based on similarity.

## Features
Restaurant Recommendation: Suggests similar restaurants by comparing reviews using cosine similarity.
Text Preprocessing: Cleanses the review data by removing stopwords, punctuation, and URLs to ensure effective analysis.
Similarity Calculation: Uses TF-IDF Vectorization and Cosine Similarity to quantify the similarity between restaurants.
Top 10 Recommendations: Returns the top 10 recommended restaurants based on their similarity scores and average ratings.
## Technologies Used
Python: The core programming language for developing the system.
Pandas: For data manipulation, cleaning, and analysis.
Scikit-learn: For implementing TF-IDF and calculating cosine similarity.
NLTK: Used for text preprocessing, including stopword removal and punctuation handling.
Matplotlib / Seaborn (optional): For data visualization (if added).
Setup and Installation
To get started with this project, clone the repository and install the required dependencies from the requirements.txt file.

## Data
The system processes a dataset containing restaurant details such as:

Restaurant Name
Location
Cuisine
Cost for two people
User Reviews
Rating
## How It Works
Input: Users input the name of a restaurant they are interested in.
Processing: The system processes the restaurant’s reviews, calculates cosine similarity between the chosen restaurant and others in the dataset, and ranks the results.
Output: The system returns the top 10 restaurants with the highest similarity to the input restaurant, along with details like cuisines, average ratings, and cost.
Preprocessing Steps
Data Cleaning: Removes unnecessary columns, duplicates, and missing values.
Text Preprocessing: Normalizes reviews by converting them to lowercase, removing punctuation, stopwords, and URLs to enhance the quality of text analysis.
Example Usage
Once set up, you can input the name of any restaurant from the dataset, and the system will provide a list of the top 10 most similar restaurants based on the reviews.
