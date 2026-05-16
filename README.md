# MNIST Digit Recognition using KNN

Classifies handwritten digits (0–9) from the MNIST dataset using a K-Nearest Neighbors (KNN) classifier.

## Tech Stack
- Python, NumPy
- Keras (TensorFlow backend) — for MNIST dataset loading (tensorflow.keras.datasets)
- scikit-learn (KNN)
- Matplotlib / Seaborn (visualization)

## Approach (Summary)
1. Load MNIST dataset (28×28 grayscale images)
2. Normalize pixel values (0–255 → 0–1)
3. Flatten images (28×28 → 784 features)
4. Train KNN (k = 3)
5. Evaluate accuracy on test set

## How to Run
Open `Digits_recognition_KNN.ipynb` in Google Colab or Jupyter Notebook and run all cells.
