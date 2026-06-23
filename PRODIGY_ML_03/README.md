# Cat vs Dog Image Classification using Support Vector Machine (SVM)

## Task Overview

This project implements a Support Vector Machine (SVM) classifier to distinguish between images of cats and dogs. The images are preprocessed by converting them to grayscale, resizing them to a fixed size, and transforming them into feature vectors suitable for machine learning.

This project was completed as part of the Machine Learning Internship Program.

## Dataset

Dataset: Cat vs Dog Dataset

Source:
https://www.kaggle.com/datasets/sanchitnamdeo/catvsdog

Dataset Structure:

```text
dataset/
│
├── train/
│   ├── Cat/
│   └── Dog /
│
└── test1/
    ├── Cat/
    └── Dog/
```

## Technologies Used

* Python
* NumPy
* OpenCV
* Scikit-Learn
* Jupyter Notebook

## Machine Learning Algorithm

Support Vector Machine (SVM)

Parameters Used:

* Kernel: RBF
* C = 10
* Gamma = Scale

## Workflow

1. Load cat and dog images from the dataset.
2. Convert images to grayscale.
3. Resize images to 64 × 64 pixels.
4. Flatten images into one-dimensional feature vectors.
5. Normalize pixel values.
6. Train the SVM classifier.
7. Evaluate the model using test data.
8. Predict whether a new image is a cat or a dog.

## Features

* Binary Image Classification
* Image Preprocessing using OpenCV
* SVM-based Classification
* Accuracy Evaluation
* Single Image Prediction

## Evaluation Metrics

The model is evaluated using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Classification Report

## Project Structure

```text
Task_03/
│
├── Task_03.ipynb
├── README.md
```

## Installation

Install required packages:

```bash
pip install -r requirements.txt
```

## Running the Project

Open the Jupyter Notebook and run all cells:

```bash
jupyter notebook
```

Then open:

```text
Task_03.ipynb
```

## Results

The trained SVM model successfully classifies cat and dog images using image pixel features and achieves satisfactory performance on the test dataset.

## Future Improvements

* Use HOG (Histogram of Oriented Gradients) features.
* Apply PCA for dimensionality reduction.
* Experiment with different SVM kernels.
* Compare results with Convolutional Neural Networks (CNNs).

## Conclusion

This project demonstrates the application of Support Vector Machines for image classification. Through image preprocessing and machine learning techniques, the model can effectively classify images as cats or dogs.

## Author

Aayush Kumar Jha

Machine Learning Internship – Task 03
