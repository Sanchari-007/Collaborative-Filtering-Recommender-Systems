# 🎬 Movie Recommender System using Collaborative Filtering
This repository contains the implementation of a Collaborative Filtering algorithm to build a movie recommender system. The project is part of a machine learning course lab and leverages matrix factorization techniques using NumPy and TensorFlow (Keras).

## 📌 Table of Contents
Overview

Technologies Used

Project Structure

How It Works

Getting Started

Output

License

**📖 Overview**

The objective of this project is to create a system that can learn user preferences and recommend movies accordingly. The system is trained on a given dataset of user-movie ratings and applies collaborative filtering to:

Predict unrated movies for users

Optimize model parameters to minimize error

Recommend top movies based on predicted preferences

**🛠 Technologies Used**
Python

NumPy

TensorFlow / Keras

Jupyter Notebook

**📁 Project Structure**

📦 movie-recommender-collaborative-filtering/

├── 📘 notebook.ipynb       # Main Jupyter Notebook

├── 📂 data/                # (If provided) Dataset files

├── 📄 README.md            # This file

**⚙️ How It Works**

Dataset Loading: Loads movie ratings by various users.

Preprocessing: Extracts useful matrices and prepares input for the model.

Cost Function: Implements the collaborative filtering cost and gradients.

Model Training: Uses optimization (Gradient Descent) to learn parameters.

Predictions: Calculates user-specific movie recommendations.

