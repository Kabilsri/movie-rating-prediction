
# Movie Success Prediction Using IMDb India Dataset

This project uses machine learning techniques to predict the success of Indian movies based on various features from the IMDb Movies India dataset.

# Overview

The goal of this project is to build a predictive model that can estimate the IMDB rating of Indian movies using features such as:

*Genre*
*Language*
*Director*
*Cast*
*Budget*
*Runtime*

#Release Year
It includes:

Data preprocessing and cleaning
Feature engineering
Model training (using algorithms like Linear Regression, Random Forest, etc.)
Model evaluation and accuracy comparison
Final prediction and visualization

# Files

File Name	Description
movie prediction.ipynb	Jupyter notebook containing full analysis and model building
IMDb Movies India.csv	Dataset containing metadata of Indian movies from IMDb

#Dataset

The dataset includes the following key features:

title: Movie title
year: Release year
genre: Genre(s) of the movie
language: Language(s) of the movie
country: Country of origin (mostly India)
director, actors: Crew involved
budget: Budget (if available)
runtime: Duration of the movie
avg_vote: IMDb rating
📌 Note: Some cleaning and transformations were performed to make the data model-ready.
🛠️ Technologies Used

*Python*
*Jupyter Notebook*
*Pandas, NumPy*
*Scikit-learn*
*Matplotlib, Seaborn*
# How to Run

# Clone the repo:
git clone https://github.com/your-username/movie-rating-prediction.git
cd movie-success-prediction

# Install dependencies (recommended in a virtual environment):
pip install -r requirements.txt
# Launch the notebook:
jupyter notebook "movie prediction.ipynb"

# Model Performance

The notebook compares multiple models and selects the best-performing one based on metrics such as:
Mean Squared Error (MSE)
R² Score
Cross-validation scores

# Future Improvements
Incorporate external data (like box office collection, social media buzz)
Add NLP-based sentiment analysis from reviews
Deploy the model via a web interface
# Author

Kabilan
Data Scientist | AI & Data Science B.Tech




