#  Online Course Recommendation System

A content-based recommendation system that suggests similar online courses using text features like title and description.

##  Overview
This project uses Natural Language Processing (NLP) techniques and cosine similarity to recommend relevant courses based on user-selected input. It’s designed for educational platforms or learners looking for similar content.

##  Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- TF-IDF Vectorizer
- Cosine Similarity
- Jupyter Notebook

##  Features
- Content-based filtering using course descriptions
- TF-IDF-based text vectorization
- Top-5 similar course recommendations

##  How It Works
1. Preprocess and vectorize course descriptions using TF-IDF
2. Compute cosine similarity between all courses
3. Select a course and retrieve the top 5 most similar ones

##  File Overview
- `Course_Recommendation_Template.ipynb` – Main notebook with all code

## 📎 Note
This is a template project — you can add your own dataset (`courses.csv`) with columns like `title` and `description`.

##  Author
Abraham Bynagari
