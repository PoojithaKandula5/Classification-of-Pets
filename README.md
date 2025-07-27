# 🐶🐱 Pet Image Classification with TensorFlow

The goal of this project is to train a deep learning model that can classify images of pets into different breeds. It leverages the Oxford-IIIT Pet Dataset, which contains images of cats and dogs with breed labels. The entire workflow — from data loading and preprocessing to model training and evaluation — is handled using TensorFlow and runs efficiently in a Google Colab environment.

---

## ✨ Key Features

- Loads and processes the Oxford-IIIT Pet Dataset using TensorFlow Datasets
- Resizes and normalizes pet images for model compatibility
- Builds a custom Convolutional Neural Network (CNN)
- Trains the model and visualizes performance metrics
- Evaluates model accuracy on a test dataset
- Easily extendable and Colab-friendly

---

## 🛠️ Technologies Used

- Python 3
- TensorFlow 2.x
- Keras API
- TensorFlow Datasets (TFDS)
- Matplotlib (for visualization)
- Google Colab (recommended for execution)

---

## 📚 Dataset

- **Name:** Oxford-IIIT Pet Dataset
- **Classes:** 37 different pet breeds (both cats and dogs)
- **Images:** Around 7,000 labeled images
- **Source:** Available through TensorFlow Datasets (`oxford_iiit_pet`)
- **Split:** 80% training, 20% testing

---

## 📊 Training Details

- **Input Size:** 128 × 128 pixels
- **Batch Size:** 32
- **Epochs:** 10
- **Model Type:** Custom CNN with multiple Conv2D and MaxPooling layers
- **Loss Function:** Sparse Categorical Crossentropy
- **Optimizer:** Adam
- **Metrics:** Accuracy (training and validation)

