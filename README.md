# 🎬 Movie Recommendation System
This project is a **content-based movie recommendation system** built using Python and Jupyter Notebook. It leverages movie metadata to suggest similar films based on content features like genres, keywords, cast, and crew.

## 💡 Features

* Reads and processes a movie dataset using **pandas**
* Combines features like **genres, overview, cast, crew, and keywords**
* Uses **TF-IDF** and **cosine similarity** to calculate similarity between movies
* Provides recommendations for a given movie title
* Includes **data preprocessing** and **feature extraction**
* Optionally uses **NLTK** for stemming and text normalization

## 📦 Dependencies

Make sure you have the following Python libraries installed:
pandas
numpy
scikit-learn
nltk
You can install them using:
pip install pandas numpy scikit-learn nltk

For first-time `nltk` users:

import nltk
nltk.download('punkt')


## 🛠 How to Run

1. Clone the repository or download the notebook.
2. Install the required dependencies.
3. Open `movie_recomd_sys.ipynb` in Jupyter Notebook or Jupyter Lab.
4. Run all cells to build the recommendation model.
5. Use the `recommend(movie_title)` function to get movie suggestions.

## 🔍 Example

```python
recommend('Inception')
```

Returns a list of movies similar to "Inception".

## 📊 Dataset

The dataset includes information like:

* Movie titles
* Overview
* Cast and crew
* Genres
* Keywords

> Note: The dataset is assumed to be loaded within the notebook. You may need to add your dataset files (`movies.csv`, `credits.csv`) if not already present.

## 🧠 Techniques Used

* Natural Language Processing (NLP)
* TF-IDF Vectorization
* Cosine Similarity
* Feature Engineering
* Stemming

## 📌 To-Do

* Improve performance with collaborative filtering
* Deploy using Streamlit or Flask
* Add genre or rating filters for recommendations

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

