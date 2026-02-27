# AI Image Search Engine

An AI-powered **Image Search Engine** that retrieves visually similar images using Deep Learning and Computer Vision.  
The system allows users to upload an image and find the most similar images from a dataset in real time.

---

## Features

- Upload an image and search for visually similar images
- Deep Learning–based feature extraction using **CLIP**
- Fast similarity search using image embeddings
- Simple web interface built with **Flask**
- End-to-end pipeline for image processing and retrieval

---

## 🧠 How it Works

1. Images are converted into **vector embeddings** using OpenAI CLIP.
2. When a user uploads a query image:
   - The image is converted into an embedding.
   - Similarity is computed against stored embeddings.
3. The system returns the **top matching images** based on similarity score.

This approach is called **Content-Based Image Retrieval (CBIR)**.

---

## 🛠️ Tech Stack

- Python
- OpenAI CLIP
- Computer Vision
- Flask (Web App)
- NumPy
- Image Embeddings & Similarity Search

---


