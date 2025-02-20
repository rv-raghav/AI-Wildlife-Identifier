AI wildlife identifer using YOLOv8, FastAPI & Streamlit
Project Overview
This project classifies animal faces into three categories: cat, dog, and wildlife using YOLOv8 for object detection. The model is trained on the Animal Faces Dataset from Kaggle.

The backend uses FastAPI for image processing, and the frontend is built with Streamlit, allowing users to upload images and view predictions. An SQLite database stores image metadata for efficient retrieval.

Key Features
YOLOv8 for real-time animal face classification.
FastAPI for backend model inference.
Streamlit UI for easy image uploads and classification.
SQLite Database to store image paths for fast lookup.
