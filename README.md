🎬 Movie Recommender System 

Welcome to the Movie Recommender System, a content-based recommendation engine that suggests movies similar to a user-selected title using Natural Language Processing (NLP) techniques.
This project uses TF-IDF, Cosine Similarity, and NLTK to process and compare movie metadata such as descriptions, genres, and tags — delivering relevant movie recommendations.

 -----------

 📌 Features
🔍 Recommends movies similar to the one you enter

🧠 Uses NLP to analyze movie metadata

🧾 Cleans and processes text using nltk

📊 Visualizes text data

💬 Based on TF-IDF + Cosine Similarity, not user ratings

-------------

🔧 Technologies Used
Python

Pandas, NumPy

NLTK – Natural Language Toolkit for text preprocessing

Scikit-learn – for TF-IDF Vectorization and Cosine Similarity

----------------

🧪 How It Works
Preprocess Movie Descriptions

Tokenization

Lowercasing

Stopword removal

Convert Text to Vectors

Apply TfidfVectorizer to transform text into numeric format

Compute Similarity

Use cosine_similarity to find movies most similar to the selected title

Recommend Movies

Return top N similar movies
