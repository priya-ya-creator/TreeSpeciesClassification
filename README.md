🌳 Tree Species Classification Assistant
An AI-powered tool that combines geolocation and computer vision to predict tree species using both GPS and leaf images.

🎯 Project Objective
To develop a smart web-based assistant that:

📍 Suggests tree species based on environmental and geographic data

📷 Identifies tree species from user-uploaded images using deep learning

🌐 Maps tree distributions across U.S. cities using big forestry datasets

🔍 Problem Overview
Traditional tree identification methods depend heavily on human expertise and manual surveys — making them inefficient and hard to scale. This project proposes a hybrid AI solution using both geolocation data and image recognition to streamline species classification.

🧠 Core Features
Location-Based Recommender
Predicts likely species using KNN and features like latitude, longitude, and native status.

Image-Based Classifier
Trained CNN model identifies species from tree images (leaves, bark, etc.)

Visual Dashboard
Streamlit-powered app offers a clean UI with real-time map and prediction outputs.

Big Data-Driven
Built on 1.38M+ urban tree records from 50+ U.S. cities.

🧰 Tech Stack
Category	Tools Used
ML & DL Frameworks	TensorFlow, scikit-learn
Data Processing	Pandas, NumPy, Matplotlib
Web App Framework	Streamlit
Model Deployment	joblib, HDF5 (.h5), Docker
Image Handling	Pillow, OpenCV, ImageDataGenerator
Geospatial Logic	KNN, GPS data, StandardScaler
