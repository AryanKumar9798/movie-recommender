# Movie Recommendation System

This is a simple movie recommendation project built using Python and the TMDB 5000 Movies dataset.  
The system suggests movies that are similar in storyline based on their plot descriptions.

---

## 📌 Project Overview
We often get confused about what to watch next after finishing a good movie.  
This project solves that problem by recommending movies which are close in theme and content to the one you liked.  
It uses **TF-IDF (Term Frequency – Inverse Document Frequency)** to convert text into numbers and then finds similarity using **cosine similarity**.

---

## ⚙️ How It Works
1. The dataset (`tmdb_5000_movies.csv`) is loaded.  
2. We keep only two important columns – movie title and overview.  
3. The text data is transformed into vectors using TF-IDF.  
4. Cosine similarity is applied to measure how close two movies are.  
5. Based on your input movie, the system shows a list of recommended titles.

---

##  How to Run
1. Clone this repository or open the notebook in **Google Colab**.  
2. Download the dataset from Kaggle:  
   [TMDB 5000 Movies Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)  
3. Upload the CSV file into your runtime (Colab or Jupyter).  
4. Run all cells in the notebook.  
5. Enter the name of any movie, and the system will recommend similar movies.

---

##  Requirements
Make sure you have the following libraries installed:


(You can install them using `pip install -r requirements.txt`)

---

##  Example
If you enter **"Avatar"**, the system might suggest other science-fiction or adventure films with similar storylines.

---

##  Future Scope
- Adding more features like cast, genre, and director for better recommendations.  
- Building a web application interface for easy use.  
- Connecting with live APIs to fetch the latest movie data.

---

## Credits
- Dataset: TMDB 5000 Movies Dataset (Kaggle)  
- Developed as a learning project to understand recommendation systems.

## Output
-<img width="666" height="230" alt="Screenshot 2025-08-22 042437" src="https://github.com/user-attachments/assets/365d064f-056f-4446-a652-6803ac002e47" />

