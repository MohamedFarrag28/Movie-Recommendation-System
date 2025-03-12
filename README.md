# 🎬 Movie Recommendation System

A personalized movie recommendation system using **collaborative filtering**, **content-based filtering**, and a **hybrid approach** to enhance user experience.

---

## 📌 Project Overview
This project utilizes the **MovieLens dataset** to build a **movie recommendation system** that suggests personalized movies to users based on their preferences. The system incorporates:

- **Collaborative Filtering** (User-based & Item-based)
- **Content-Based Filtering** (TF-IDF on genres)
- **Hybrid Model** (Combining both methods)
- **SVD-based Collaborative Filtering** (Optional)

---

## 📂 Project Structure

```
Movie-Recommendation-System/
│── Data/
│   ├── raw/               # Original dataset files (movies.csv, ratings.csv, etc.)
│   ├── processed/         # Preprocessed files (e.g., TF-IDF matrix)
│
│── notebooks/             # Jupyter Notebooks for implementation
│── reports/               # Evaluation results & visualizations
│   ├── Similarity_Heatmaps/  # Similarity matrices & visual insights
│   ├── Model_Evaluations.png
│   ├── Movie_Recommendation_System.pdf
│
│── README.md              # Project Documentation
│── requirements.txt       # Dependencies list
```

---

## 📊 Features & Methodology

✔ **Exploratory Data Analysis (EDA)**  
- Understanding user preferences  
- Visualizing rating distributions & popular movies  

✔ **Collaborative Filtering**  
- User-based similarity  
- Item-based similarity  
- Cosine Similarity  

✔ **Content-Based Filtering**  
- TF-IDF on movie genres  
- Cosine similarity for recommendations  

✔ **Hybrid Model**  
- Merging collaborative & content-based methods for improved recommendations  

✔ **SVD Model (Optional)**  
- Singular Value Decomposition using Surprise Library  
- Evaluated with RMSE and MAE  

---

## 🚀 Installation & Usage

### 🔹 Clone the Repository
```bash
git clone https://github.com/MohamedFarrag28/Movie-Recommendation-System.git
cd Movie-Recommendation-System
```

### 🔹 Install Dependencies
```bash
pip install -r requirements.txt
```

### 🔹 Run Jupyter Notebook
```bash
jupyter notebook
```
Open `Movie_Recommendation_System.ipynb` to explore the implementation.

---

## 📈 Evaluation Metrics

The recommendation system is evaluated using:

📌 **Mean Absolute Error (MAE)**  
📌 **Root Mean Squared Error (RMSE)**  

📊 **Visualization Reports:**  
✅ Similarity Heatmaps (User-Item, Item-Item)  
✅ Model Performance Comparisons  

---

## 🔥 Future Improvements
- Enhance hybrid model tuning for better accuracy  
- Implement deep learning techniques (e.g., Neural Collaborative Filtering)  
- Deploy the system with **Flask/Streamlit** for real-time recommendations  

---

## 📚 References

- **MovieLens Dataset**: [MovieLens](https://grouplens.org/datasets/movielens/)  
- **Surprise Library**: [Surprise Documentation](https://surprise.readthedocs.io/en/stable/)  

