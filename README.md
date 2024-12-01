# 🎥 Movie Recommendation System

This project is a **Personalized Movie Recommendation System** built using the **TMDB 5000 Movie Dataset**. It leverages **Natural Language Processing (NLP)**, **Machine Learning**, and **Data Visualization** to provide personalized movie recommendations. The system is designed to enhance user experience by suggesting movies similar to user preferences.

---

## 📖 Table of Contents

1. [Introduction](#introduction)
2. [Objective](#objective)
3. [Key Features](#key-features)
4. [Workflow](#workflow)
5. [Technologies and Libraries Used](#technologies-and-libraries-used)
6. [Setup Instructions](#setup-instructions)
7. [Acknowledgments](#acknowledgments)
8. [Contact](#contact)

---

## 📝 Introduction

With the rise of online streaming platforms, personalized recommendations have become a cornerstone of the entertainment industry. This **Movie Recommendation System** analyzes metadata like genres, cast, crew, and movie overviews to suggest movies tailored to user preferences. By implementing advanced techniques studied throughout the semester, this project combines theoretical knowledge with practical applications.

---

## 🎯 Objective

The goal of this project is to build a **hybrid recommendation system** that:
- Suggests movies based on metadata such as genres, cast, crew, and overviews.
- Applies NLP techniques like Named Entity Recognition (NER) and Sentiment Analysis.
- Combines features for enhanced recommendations using machine learning.
- Visualizes trends in movie genres, ratings, and sentiments.

---

## ⭐ Key Features

1. **Content-Based Recommendations**:
   - Suggest movies similar to a user-selected movie.
2. **NLP Techniques**:
   - Extract entities from descriptions using NER.
   - Analyze movie overviews using Sentiment Analysis.
3. **Hybrid Recommendations**:
   - Combine metadata features with textual analysis for improved results.
4. **Interactive Interface**:
   - Users can input their favorite movie to get real-time recommendations.
5. **Data Visualization**:
   - Explore trends in genres, ratings, and sentiment distributions.
6. **Real-World Dataset**:
   - Based on the TMDB 5000 Movie Dataset.

---

## 🛠️ Workflow

### **1. Data Preparation and EDA**
- Load and inspect the TMDB dataset.
- Handle missing values and clean data.

### **2. Data Cleaning and Preprocessing**
- Parse JSON-like columns for genres, cast, and crew.
- Combine metadata and descriptions into a unified feature.

### **3. Natural Language Processing (NLP)**
- **TF-IDF Vectorization**: Analyze movie overviews for importance.
- **NER**: Extract key elements (names, places, organizations) from descriptions.
- **Sentiment Analysis**: Determine the sentiment polarity of overviews.

### **4. Recommendation System**
- **Content-Based Recommendations**: Use cosine similarity to recommend movies.
- **Hybrid Recommendations**: Combine multiple features for accuracy.

### **5. Visualization**
- Visualize genre distributions, sentiment polarity, and trends.

### **6. User Interaction**
- Interactive input for real-time recommendations.

### **7. Deployment**
- Organized project structure with GitHub and a YouTube walkthrough.

---

## 🛠️ Technologies and Libraries Used

- **Programming Language**: Python
- **Libraries**:
  - **Data Handling**: Pandas, NumPy
  - **Visualizations**: Matplotlib, Seaborn
  - **NLP**: spaCy, TextBlob, scikit-learn
  - **Machine Learning**: scikit-learn
- **Tools**:
  - Jupyter Notebook for development.
  - GitHub for version control.
  - YouTube for project demo.

---

## ⚙️ Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/movie-recommendation-system.git
   cd movie-recommendation-system

# 💡 Acknowledgments
- Dataset: TMDB 5000 Movie Dataset from Kaggle.
- Libraries: spaCy, TextBlob, scikit-learn, Pandas.
- Inspired by techniques learned in CISB 63.
