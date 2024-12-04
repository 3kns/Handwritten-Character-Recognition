# Handwritten Alphabet Recognition

This project uses a Convolutional Neural Network (CNN) to classify handwritten alphabet images into 26 classes (A-Z). The dataset is processed, and a deep learning model is trained using Keras.

---

## Features
- Preprocessing and visualization of the dataset.
- Deep learning model implementation using CNNs.
- Training and evaluation of the model.
- Prediction for new input images.

---

## Dataset
The dataset used is `A_Z Handwritten Data.csv`, containing labeled data for alphabets (A-Z). Each letter is represented as a grayscale image.

---

## Requirements
The project requires the following:
- Python 3.7 or higher.
- Libraries listed in `requirements.txt`.

---

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your_username/handwritten-alphabet-recognition.git
   cd handwritten-alphabet-recognition
Install the dependencies:

pip install -r requirements.txt
Place the dataset (A_Z Handwritten Data.csv) and sample test image (w.jpg) in the project folder.

Usage
Run the training script:

python train_model.py
Predict a single image: Use the preprocess_image function to preprocess and predict a test image. Replace 'w.jpg' with your image path:

test_image = preprocess_image('your_image.jpg')
prediction = model.predict(test_image)
Output
Training and Validation Metrics: Accuracy and Loss plots.
Model File: Saved as model_hand.h5.
Test Predictions: Predictions are displayed for test samples.