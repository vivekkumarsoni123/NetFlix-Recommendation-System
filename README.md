# Netflix Recommendation System

A **real-time movie recommendation system** implemented in a Jupyter Notebook. It suggests movies based on genre similarity using TF-IDF vectorization and cosine similarity.

---

##  Repository Contents

- `NetFlix_Recommendation_System.ipynb` – Jupyter Notebook containing the complete pipeline: data preprocessing, vectorization, similarity computation, and recommendation logic.
- `netflixData.csv` – Dataset containing movie titles, genres, and additional metadata as input for generating recommendations.

---

##  Features

- **Genre-based similarity**: Suggests movies by analyzing genre overlap using NLP techniques.
- **TF-IDF Vectorization**: Converts movie genres into numerical vectors for efficient comparison.
- **Cosine Similarity**: Calculates similarity scores between movies to identify the closest matches.
- **Interactive Notebook**: Run and tweak the model directly in Jupyter to explore results and customize recommendations.

---

##  How It Works

1. **Load Data**  
   Import the CSV dataset containing movie titles and genre information.

2. **Preprocess Genres**  
   Use TF-IDF to convert genre strings into vectorized representations.

3. **Compute Similarity**  
   Calculate cosine similarity between all movies based on their TF-IDF genre vectors.

4. **Recommend Movies**  
   For a given movie title, return the top N most similar titles based on similarity scores.

---

## Screen Shots
![Anomaly_1](https://github.com/user-attachments/assets/4a742ba1-89bf-4cc1-b948-f5226eeb90ee)
![Anomaly_2](https://github.com/user-attachments/assets/7fae02eb-84bf-446b-b54c-2ee5352168f9)
![Anomaly_3](https://github.com/user-attachments/assets/8a0387c7-8d55-49a8-8f17-c25b6bc23d65)
![Anomaly_4](https://github.com/user-attachments/assets/ba47842b-26fb-4d1b-9ddc-bc3fe39a5f92)

---

##  Setup & Usage

1. **Clone the Repo**
   ```bash
   git clone https://github.com/vivekkumarsoni123/NetFlix-Recommendation-System.git
   cd NetFlix-Recommendation-System
````

2. **Create a Virtual Environment (optional but recommended)**

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate     # Windows
   ```

3. **Install Required Packages**

   ```bash
   pip install numpy pandas scikit-learn jupyter
   ```

4. **Run the Notebook**

   ```bash
   jupyter notebook NetFlix_Recommendation_System.ipynb
   ```

5. **Get Recommendations**
   Open the notebook and use the provided functions to input a movie title and retrieve recommendations in real time.

---

## Example Usage

```python
recommend_movies("The Matrix", top_n=5)
```

This should return a list of 5 movies with genres most similar to *The Matrix*.

---

## Future Enhancements

* Integrate additional metadata such as plot summaries or cast to improve recommendation accuracy.
* Implement a web-based UI (using Flask or Streamlit) for interactive user access.
* Store precomputed similarity matrices for faster lookup and scaling.

---

## About

**Author:** Vivek Kumar Soni
Explore more:

* [GitHub](https://github.com/vivekkumarsoni123)
* [LinkedIn](https://linkedin.com/in/vivek-kumar-soni-9b2591258)

---


