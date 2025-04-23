# Movie-Recommender-System-with-MOVIE-POSTERS
https://colab.research.google.com/drive/1BMeRqN5PN_2DOOdJGXIMTlYKoZvBxRiJ#scrollTo=YKBIk1Rk2SCi

---
<img width="1470" alt="Screenshot 2025-04-23 at 3 32 20 PM" src="https://github.com/user-attachments/assets/f6331bfe-2f23-45c1-b798-424ba745bc85" />
<img width="1470" alt="Screenshot 2025-04-23 at 3 32 29 PM" src="https://github.com/user-attachments/assets/12b2a0b8-778d-45d2-b478-7b049c71ac3c" />
<img width="1470" alt="Screenshot 2025-04-23 at 3 32 40 PM" src="https://github.com/user-attachments/assets/6659958b-9fa1-41ac-9ee8-c2636fe466a8" />
<img width="1470" alt="Screenshot 2025-04-23 at 3 32 48 PM" src="https://github.com/user-attachments/assets/5e9ca788-7e93-45a5-b96e-f0b0fc69fb37" />
<img width="1470" alt="Screenshot 2025-04-23 at 3 33 00 PM" src="https://github.com/user-attachments/assets/aebcb918-4d26-4908-ac6b-fe39f43d57aa" />
<img width="1470" alt="Screenshot 2025-04-23 at 3 33 17 PM" src="https://github.com/user-attachments/assets/92c054ad-1878-4544-87b8-5cb1b5391f8c" />





---
**Data Sources**

https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata
* movies.csv: Contains metadata such as movie titles, genres, overviews, etc.
* credits.csv: Contains additional details like cast and crew.
---
**Workflow Overview**

1. Data Loading & Merging
2. Feature Engineering
* Extract and clean important metadata:
    * Genres
    * Keywords
    * Cast Members
* Combine all relevant features into a single column called tags.
3. Text Processing
* Remove spaces and special characters.
* Vectorize the text data using CountVectorizer to create feature vectors.
4. Similarity Calculation
* Calculate cosine similarity between all movies based on their tag vectors.
5. Recommendation Function
* Given a movie title, retrieve its most similar movies.
* Display top 5 recommendations.
---
**Output**

* A function to fetch top 5 movie recommendations.
* Cosine similarity matrix for movie similarity.

---
**Tech-Stack**

1. **Data Science & Machine Learning Python** : Core language for data processing and modeling.
Pandas: Data manipulation.
NumPy: Numerical computations.


2. **Scikit-learn** : i.CountVectorizer - Text vectorization , ii.cosine_similarity - To measure movie similarity.


3. **NLTK** : For advanced text preprocessing like stemming.


4. **Streamlit** : for basic web UI and application.

5. **API-KEY from TMDB**
---
