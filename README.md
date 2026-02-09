# Movie Recommendation
Movie Recommendation System 🎬
A machine learning-based recommendation engine that suggests movies similar to a user's favorites. This project uses Natural Language Processing (NLP) to analyze movie metadata and calculate similarity between titles.

🚀 Overview
This system utilizes a Content-Based Filtering approach. It processes movie features (overview, genres, keywords, cast, and crew) to create a "tags" column, which is then converted into vectors to find the closest matches in a multi-dimensional space.

🛠️ Tech Stack
Language: Python

Libraries: * pandas & numpy (Data Manipulation)

scikit-learn (Vectorization & Cosine Similarity)

nltk (Stemming/Text Processing)

Streamlit (Optional: for the Web UI)

📊 How it Works
Data Preprocessing: Cleaning missing values and converting strings into lists of keywords.

Feature Engineering: Merging columns (Genres + Overview + Cast + Crew) into a single tags column.

Vectorization: Using CountVectorizer to convert text into a 5000-dimensional vector space.
