# Movie-Recommendation-App
🎬 Content-Based Movie Recommendation System
📝 Overview
------------
This project implements a content-based movie recommendation system that suggests movies similar to a given title using movie metadata (genres, keywords, and plot descriptions). It leverages:

🧠 NLP preprocessing (tokenization, stop-word removal, normalization)  
📊 TF-IDF vectorization (5,000 features)  
🤝 Cosine similarity for top-N recommendations  

🚀 Features:
------------
🎯 Generates top-5 relevant movie recommendations  
📂 Processes 4,300+ movies and 15K+ text features  
📊 Performs EDA and visualization with WordClouds, Matplotlib, and Pandas  
⚡ Real-time recommendation (<100 ms/query)  

📂 Dataset:
-----------
CSV format: movies.csv  
Key columns: title, genres, keywords, overview  
Cleaned dataset: 4,387 movies  

💻 Technology Stack:
--------------------
Python  
Pandas  
NumPy  
NLTK  
Scikit-learn  
Matplotlib  
WordCloud  
