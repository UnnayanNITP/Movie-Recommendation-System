Movie Recommendation System 🎥
A content-based movie recommendation system that provides movie suggestions based on user preferences, utilizing movie metadata like cast, crew, genre, and more to compute similarity between movies.

Features ✨
Context-based Recommendations: Recommends movies by analyzing movie metadata such as cast, director, genre, and language.
Text Input Matching: Users can input a movie title to receive similar movie suggestions.
Vectorization: Uses TF-IDF vectorization to convert movie tags into numerical representations.
Web-based Interface: Simple and intuitive user interface built using Streamlit.
Technologies Used 🛠️
Backend:
Python (Numpy, Pandas)
Scikit-learn (for vectorization and similarity calculation)
Frontend:
Streamlit (for creating the web interface)
How It Works 🚀
Data Preprocessing: Extracts movie metadata such as cast, director, and genre to create a tag for each movie.
Vectorization: The metadata is transformed into numerical vectors using TF-IDF.
Similarity Calculation: Cosine similarity is applied to find movies that are most similar to the one the user has input.
Recommendations: The system displays movies with the highest similarity scores based on the input provided by the user.

