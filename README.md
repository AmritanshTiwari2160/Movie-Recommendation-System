# 🎬 Movie Recommendation System

Welcome to the **Movie Recommendation System** project! This application is designed to suggest movies based on your preferences using advanced similarity measures. Built with Python, FastAPI, and Streamlit, this project leverages efficient data handling techniques to provide quick and accurate recommendations.

## 🌟 Features

- **Movie Recommendations:** Suggests movies similar to your selected title using a custom recommendation algorithm.
- **Streamlit Interface:** User-friendly interface to select movies and view recommendations.
- **Efficient Data Handling:** Handles large datasets by splitting them into manageable chunks for optimized performance.
- **FastAPI Backend:** A robust and scalable API that serves movie recommendations.
- **Pickle Serialization:** Efficient data storage and retrieval using Python's `pickle` module.

## 🛠️ Technologies Used

- **Python**
- **FastAPI**
- **Streamlit**
- **Pandas**
- **Pickle**
- **OS**

## 🚀 How It Works

### Data Preparation:

- The dataset is loaded and processed to compute similarity scores between movies.
- The large similarity matrix is split into smaller chunks for efficient storage and retrieval.

### Recommendation Logic:

- When a user selects a movie, the system identifies similar movies by calculating distances in the similarity matrix.
- The top recommendations are then displayed to the user.

### Deployment:

- The backend API is powered by FastAPI, ensuring that the recommendation system can handle multiple requests efficiently.
- The frontend interface is built with Streamlit, allowing users to interact with the system seamlessly.

## 📂 Project Structure

- **main.py:** FastAPI backend that handles API requests and serves movie recommendations.
- **app.py:** Streamlit frontend that provides a user interface for selecting movies and viewing recommendations.
- **model/:** Directory containing serialized model files (e.g., `movie_dict.pkl`, `similarity.pkl`) and data chunks.
- **requirements.txt:** List of required Python packages.
