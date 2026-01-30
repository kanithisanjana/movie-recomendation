# movie-recomendation
Content-Based Movie Recommendation System using TF-IDF and Cosine Similarity with an interactive Jupyter widget interface.
# 🎬 Movie Recommendation System (Content-Based)

This project is a **Content-Based Movie Recommendation System** built using Python and Machine Learning techniques. It recommends movies similar to a selected movie by analyzing movie metadata such as **overview, genres, and keywords**.

The system uses **TF-IDF Vectorization** to extract important textual features and **Cosine Similarity** to compute similarity between movies. An interactive **dropdown-based UI** is provided using `ipywidgets` in a Jupyter Notebook for easy movie selection and recommendation.

---

## 🚀 Features
- Content-based filtering (no user ratings required)
- Uses **TF-IDF** for text feature extraction
- **Cosine Similarity** for finding similar movies
- Interactive dropdown UI using **IPyWidgets**
- Top 5 movie recommendations for selected movie

---

## 🛠️ Technologies Used
- **Python**
- **Pandas**
- **Scikit-learn**
- **IPyWidgets**
- **Jupyter Notebook**

---

## 📂 Dataset
- **TMDB 5000 Movies Dataset**
- Includes the following features:
  - Movie Title
  - Overview
  - Genres
  - Keywords

---

## ⚙️ How It Works
1. Load and preprocess the movie dataset
2. Extract and clean genres and keywords
3. Combine text features into a single column
4. Apply **TF-IDF Vectorizer** to transform text data
5. Calculate **Cosine Similarity Matrix**
6. Recommend top 5 similar movies based on similarity score
7. Display results interactively using dropdown and button

---

## ▶️ How to Run the Project
1. Clone the repository
2. Install required libraries
3. Open Jupyter Notebook
4. Run all cells in the notebook
5. Select a movie from the dropdown and click Get Recommendations
   ```bash
   git clone https://github.com/your-username/movie-recommendation-system.git
   pip install pandas scikit-learn ipywidgets
   jupyter notebook

## Sample Output:
   Recommended movies for 'Avatar':

1. Guardians of the Galaxy
2. Star Trek
3. John Carter
4. Interstellar
5. The Avengers


🔮 Future Enhancements
1. Add movie posters and ratings
2. Include cast and crew information
3. Improve text preprocessing
4. Deploy as a web application using Streamlit or Flask

👩‍💻 Author

Kanithi Sanjana

⭐ If you like this project, consider giving it a star!
