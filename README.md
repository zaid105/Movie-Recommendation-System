# **Content Based Movie Recommendation System**
<br>
<img src="https://user-images.githubusercontent.com/33485020/108069438-5ee79d80-7089-11eb-8264-08fdda7e0d11.jpg">
<br><br>

## Source
-[TMDB Movie 5000 Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
<br>
## Features
  'budget', 'genres', 'homepage', 'id', 'keywords', 'original_language',
       'original_title', 'overview', 'popularity', 'production_companies',
       'production_countries', 'release_date', 'revenue', 'runtime',
       'spoken_languages', 'status', 'tagline', 'title', 'vote_average',
       'vote_count', 'movie_id', 'cast', 'crew'

# Overview:
In the era of streaming services and vast movie libraries, finding movies tailored to individual preferences can be a daunting task. To address this challenge, we developed a content-based movie recommendation system leveraging advanced vectorization techniques and the Porter Stemmer algorithm. By analyzing the content and features of movies, our system suggests personalized recommendations based on the user's preferences and viewing history.

# Techniques Used:

Vectorization: We employed vectorization techniques to convert textual features such as movie plots, genres, and cast information into numerical representations. This allowed us to quantify the similarities between movies based on their content.


Porter Stemmer: The Porter Stemmer algorithm was applied to reduce words to their base or root form, enabling us to handle variations of words and improve the accuracy of our recommendations.

Cosine Similarity: We computed the cosine similarity between the vectorized representations of movies to measure their similarity. This enabled us to recommend movies that are most similar to the ones the user has already enjoyed.

Data Preprocessing: Prior to vectorization, we performed data preprocessing tasks such as text cleaning, tokenization, removing stop words, and applying the Porter Stemmer algorithm to enhance the quality of our recommendations.


# Conclusion:
Our content-based movie recommendation system offers users a seamless and personalized movie discovery experience. By leveraging advanced vectorization techniques and the Porter Stemmer algorithm, we can accurately capture the essence of each movie and provide tailored recommendations that match the user's interests and preferences.

<br><br>
  <img src="https://miro.medium.com/max/1400/1*wI-ykF0AGtYrz-TGdx5fNQ.png">
