# Unsupervised-ML---Netflix-Movies-and-TV-Shows-Clustering

# 🎬 Netflix Movies & TV Shows Clustering using Unsupervised Machine Learning

## 📌 Project Overview

This project applies **unsupervised machine learning techniques** to analyze and cluster Netflix movies and TV shows based on their content-related attributes. The objective is to discover hidden patterns and group similar titles together, helping to better understand Netflix’s content distribution and support recommendation-style insights.

The project is implemented entirely in **Python using Jupyter Notebook** and demonstrates a complete ML workflow including data preprocessing, exploratory data analysis (EDA), feature engineering, clustering, and evaluation.

---

## 🎯 Problem Statement

Netflix hosts a massive and diverse collection of movies and TV shows. Manually analyzing similarities across content types is inefficient. This project aims to:

* Identify natural groupings of Netflix titles
* Cluster similar movies and TV shows based on features
* Understand content patterns across genres, duration, and release trends

---

## 📂 Dataset Information

* **Dataset Name:** Netflix Movies and TV Shows
* **Source:** Public Netflix dataset (CSV file)
* **Description:** The dataset contains information about Netflix titles including type (Movie/TV Show), genre, country, release year, rating, duration, and description.

---

## 🛠 Tools & Technologies

* **Python**
* **Pandas & NumPy** – Data handling and preprocessing
* **Matplotlib & Seaborn** – Visualization
* **Scikit-learn** – Machine learning and clustering algorithms
* **Jupyter Notebook** – Development environment

---

## 🧹 Data Cleaning & Preprocessing

* Handled missing and null values
* Removed unnecessary columns
* Encoded categorical variables
* Transformed text-based features
* Scaled numerical features for clustering

---

## 🔄 Methodology

1. Data Loading and Inspection
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Data Scaling
5. Clustering using Unsupervised ML algorithms
6. Cluster evaluation and interpretation

---

## 🤖 Machine Learning Models Used

* **K-Means Clustering**
* **Hierarchical Clustering**

The optimal number of clusters was identified using:

* Elbow Method
* Silhouette Score

---

## 📊 Key Insights

* Netflix titles can be grouped into meaningful clusters based on content attributes
* Certain clusters reveal similarities between movies and TV shows
* Clustering helps understand content segmentation and viewer targeting

---

## 🚀 How to Run the Project

1. Clone the repository
2. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open the notebook:

   ```bash
   jupyter notebook
   ```
4. Run all sequentially

---

## 🔮 Future Improvements

* Apply advanced NLP techniques on title descriptions
* Experiment with DBSCAN and other clustering algorithms
* Build a recommendation system using clusters
* Deploy results using a dashboard or web app

---

## 📄 License

This project is created for **educational and portfolio purposes**. You are free to use and modify it for learning.

---

⭐ If you find this project helpful, consider giving it a star on GitHub!
