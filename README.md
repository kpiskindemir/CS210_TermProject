# Spotify Top Songs 2023 Data Analysis

This project includes analysis of data on the Spotify songs I listened to most in 2023. Within the scope of the project, the data set was discovered, cleaned, visualized and a machine learning model was created.

## Project Phases

### Data Discovery and Cleansing
- **Dataset Information:** CSV file named `top_songs_2023.csv` was used.
- **Null Values:** Null values in the data set were examined and necessary cleaning was done.
- **Popularity Ranking:** The top 10 songs in the data set are listed according to their popularity ranking.
- **Dataset Statistics:** Basic statistics of the dataset have been calculated.

### Visualizations
- **Popularity Distribution:** Histogram showing the distribution of song popularity.
- **Popularity and Danceability Relationship:** Scatter plot showing the relationship between popularity and danceability.
- **Top 10 Songs:** List of the 10 most popular songs.
- **Correlation Matrix:** Heat map showing correlations between numerical features.
- **Artist Distribution:** Bar plot showing the distribution of artists.
- **Artist and Year Relationship:** Heatmap showing the average popularity of artists by year.
- **Average Popularity by Years:** Line chart showing the average popularity of songs by years.

### Machine Learning Model
- **Target Variable:** Popularity.
- **Arguments:** Disc number, song number, explicit, artist name, album name, album artist name.
- **Model:** Decision Tree Regressor.
- **Model Performance:** Mean square error (MSE) on the test set.

## Use

You can follow the steps below to run the project on your own computer:

1. Clone the repo: `git clone https://github.com/username/proje.git`
2. Create a virtual environment using Anaconda or virtualenv.
3. Install the required dependencies: `pip install -r requirements.txt`
4. Perform analysis and model creation via Jupyter Notebook or Python script.
