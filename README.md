# 🎬 Content-Based Movie Recommender System (Netflix Dataset)

This project provides a Jupyter Notebook that implements a simple yet effective **Content-Based Movie Recommender System**. It uses metadata (like director, cast, and description) from a dataset of Netflix titles to recommend similar movies to a user based on their selection.

---

## 🎯 Project Goals

The main objective is to build a functional recommender system pipeline, demonstrating key Natural Language Processing (NLP) and similarity techniques:

1.  **Data Preprocessing:** Clean and structure the movie metadata, filling missing values and combining relevant textual features.
2.  **Text Vectorization:** Convert the descriptive text (combined features) into a numerical format suitable for comparison using the **TF-IDF (Term Frequency-Inverse Document Frequency) Vectorizer**.
3.  **Similarity Calculation:** Calculate the pairwise similarity between all movies using the **Cosine Similarity** metric.
4.  **Recommendation Engine:** Create a function that takes a movie title and returns the top N most similar movies based on their content vectors.

## ⚙️ Technology Stack and Dependencies

The project relies on standard Python libraries for data manipulation and machine learning:

| Library | Role |
| :--- | :--- |
| **`pandas` & `numpy`** | Data loading, manipulation, and numerical operations. |
| **`sklearn.feature_extraction.text`** | Used for the **TF-IDF Vectorizer** to transform text into feature vectors. |
| **`sklearn.metrics.pairwise`** | Used to calculate the **Cosine Similarity** matrix between movie feature vectors. |

### Installation
```bash
pip install pandas numpy scikit-learn
```bash
pip install pandas numpy scikit-learn
