# Image-Text-Matching-using-CLIP
This project demonstrates **image understanding using OpenAI's CLIP model** through the `sentence-transformers` library. The model compares an input image with multiple text descriptions and predicts the caption that best matches the image based on semantic similarity.

## 📌 Features

- Load and display images using Pillow and Matplotlib
- Generate embeddings for both images and text
- Compare images with multiple text descriptions
- Find the most relevant caption using cosine similarity
- Visualize the image along with the predicted description

## 🛠️ Technologies Used

- Python
- Google Colab
- Sentence Transformers
- CLIP (clip-ViT-B-32)
- NumPy
- Pillow (PIL)
- Matplotlib

## 📂 Project Workflow

1. Load the pre-trained CLIP model.
2. Read an input image.
3. Define multiple text descriptions.
4. Convert both the image and text into embeddings.
5. Calculate similarity scores between the image and each description.
6. Select the description with the highest similarity score.
7. Display the image and its predicted caption.

## 📊 Example

**Input:**  
An image containing a developer working with multiple monitors.

**Candidate Descriptions:**
- A cat on a table
- A picture of London at night
- A developer working on code with multiple monitors
- A dog sleeping on a couch
- Colorful hot air balloons floating in the sky

**Output:**

```text
Best Match:
"A developer working on code with multiple monitors"
```

## 📚 Concepts Used

- Computer Vision
- Image Embeddings
- Text Embeddings
- CLIP Model
- Semantic Similarity
- Image-Text Matching

## 🎯 Learning Outcome

This project demonstrates how CLIP can understand the relationship between images and natural language. It provides a practical introduction to multimodal AI by matching images with text descriptions using embedding similarity instead of traditional image classification.

---
⭐ If you found this project useful, consider giving it a star!
