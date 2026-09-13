# 🎬 Movie Recommender System

A content-based Movie Recommender System built using Python and Streamlit.

## 🚀 Live Demo

https://movie-recommender-system-ixr6e9otawvuhjj8qhthgh.streamlit.app/

## 📌 About the Project

This project recommends movies based on the similarity between movies in the dataset.

The user selects a movie from the dropdown menu and clicks the **Recommend** button. The system then displays five movies that are most similar to the selected movie.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Pickle

## ⚙️ How It Works

1. Movie data is loaded using Pickle and Pandas.
2. A pre-computed similarity matrix is loaded.
3. The user selects a movie.
4. The system finds the selected movie's index.
5. Similarity scores are retrieved.
6. Movies are sorted according to their similarity scores.
7. The top five similar movies are displayed.

## 💻 Run Locally

Clone the repository:

```bash
git clone https://github.com/chauhanprachi025-ui/movie-recommender-system.git