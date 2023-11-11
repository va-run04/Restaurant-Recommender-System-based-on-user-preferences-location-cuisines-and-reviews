# Restaurant-Recommender-System-based-on-user-preferences-location-cuisines-and-reviews

## Overview
This project implements a restaurant recommendation system based on user preferences, location, and cuisine type using a combination of natural language processing techniques and machine learning. The recommendation system analyzes restaurant data from the Zomato dataset, preprocesses the text, calculates popularity scores, and utilizes cosine similarity to suggest top restaurants.

## Key Features

-**Data Set:**
  - Here is the link for the data set [(https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants?select=zomato.csv)] download the larger file which is around 570MB
    
- **Data Loading and Preprocessing:**
  - Load restaurant data from the Zomato dataset.
  - Handle missing values and clean text data by converting to lowercase, removing special characters, and punctuation.

- **Feature Engineering:**
  - Categorize ratings into 'good', 'average', and 'bad'.
  - Extract and process ratings from the 'reviews_list' column.
  - Create new columns for different rating categories and calculate the percentage of each category.

- **Text Data Cleaning:**
  - Utilize NLTK for text processing, including HTML stripping, removing square brackets, denoising, and lemmatization.
  - Remove stopwords and non-ASCII characters, replace numbers, and handle punctuation.

- **Popularity Score Calculation:**
  - Calculate a popularity score based on weighted ratings to measure a restaurant's overall popularity.

- **Visualization:**
  - Generate histograms for the distribution of ratings.
  - Display top restaurants based on popularity score.
  - Create a word cloud for reviews.
  - Plot bar charts for average ratings and popularity scores based on restaurant types.

- **User Recommendation:**
  - Implement a user-friendly recommendation function.
  - Take user preferences for text, location, and cuisine type as input.
  - Use cosine similarity to recommend top restaurants based on user input.

## Libraries Used
- Pandas
- NumPy
- Scikit-learn
- NLTK
- BeautifulSoup
- Matplotlib
- Seaborn
- WordCloud

## Notes
- The Zomato dataset is used for demonstration purposes.
- Ensure that the necessary datasets and libraries are available before running the script.
