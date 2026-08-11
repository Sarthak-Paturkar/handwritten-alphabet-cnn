# Handwritten Alphabet Classification using CNN

A basic CNN project for classifying handwritten English alphabets (A-Z) using Python and TensorFlow/Keras.

## Dataset

The dataset contains 372,451 handwritten alphabet images.

Each image is:
- 28 × 28 pixels
- Grayscale
- 784 pixel values
- One of 26 classes (A-Z)

## Project Workflow

1. Load the dataset
2. Understand the dataset
3. Separate images and labels
4. Normalize pixel values
5. Reshape images to 28 × 28 × 1
6. Split data into training and testing sets
7. Build a CNN
8. Train the model
9. Evaluate the model
10. Test handwritten alphabet predictions

## Model

The CNN consists of:
- Convolutional layers
- Max Pooling layers
- Flatten layer
- Dense layer
- Dropout
- Softmax output layer for 26 classes

## Results

- Test Accuracy: **99.24%**
- Number of Classes: **26**
- Image Size: **28 × 28**
- Image Type: **Grayscale**

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Pillow
- Jupyter Notebook

## What I Learned

- Understanding image data as pixel values
- Working with grayscale images
- Image normalization and reshaping
- Preparing data for CNNs
- Building and training a CNN
- Model evaluation
- Making predictions on handwritten images
- Understanding the importance of preprocessing and data distribution

## Note

The original CSV dataset is not included in this repository because of its large size.

The model was trained and tested using the handwritten alphabet dataset.