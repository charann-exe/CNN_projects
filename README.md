# CNN_projects
# 🧠 Image Classification with TensorFlow

This project demonstrates two deep learning models built using TensorFlow and Keras:
1. 🐴🐶 Horse vs Human Image Classification
2. 🐱🐶 Cat vs Dog Image Classification

These models are trained on labeled image datasets to classify whether an image contains a **horse or a human**, and a **cat or a dog**, respectively.

---

## 🚀 Features

- Built with **TensorFlow 2.x** and **Keras**
- Uses **ImageDataGenerator** for data augmentation and preprocessing
- Classifies images with high accuracy
- Includes training, validation, and prediction scripts
- Easy to run in Jupyter Notebook or Google Colab

---

## 📂 Dataset

- **Horse vs Human**: Provided by [Google Developers](https://storage.googleapis.com/laurencemoroney-blog.appspot.com/horse-or-human.zip)
- **Cat vs Dog**: Based on [Microsoft’s Kaggle Cats and Dogs Dataset](https://www.microsoft.com/en-us/download/confirmation.aspx?id=54765)

---

## 🛠️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
📊 How It Works
1. Horse vs Human Classifier
Download and unzip dataset

Normalize and augment images

Build a CNN model using Keras Sequential API

Train the model and evaluate accuracy

Use model to predict new unseen images

2. Cat vs Dog Classifier
Use the Microsoft cats vs dogs dataset

Preprocess data using ImageDataGenerator

Train a CNN with dropout and multiple Conv2D layers

Save the model and use it for real-time predictions

