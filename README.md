# Cats vs Dogs Image Classification using Support Vector Machine (SVM)

Welcome to the repository for our project on classifying images of cats and dogs using a Support Vector Machine (SVM). This project was developed by the team at Prodigy Infotech.

## Table of Contents

- [Cats vs Dogs Image Classification using Support Vector Machine (SVM)](#cats-vs-dogs-image-classification-using-support-vector-machine-svm)
  - [Table of Contents](#table-of-contents)
  - [Project Overview](#project-overview)
  - [Dataset](#dataset)
  - [Preprocessing](#preprocessing)
  - [Model Implementation](#model-implementation)
  - [Results](#results)
  - [Visualization](#visualization)
    - [How to Use](#how-to-use)
  - [Conclusion](#conclusion)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Contributing](#contributing)

## Project Overview

The aim of this project is to classify images of cats and dogs using a Support Vector Machine (SVM). We utilize the popular dataset from Kaggle's Dogs vs. Cats competition.

## Dataset

The dataset can be downloaded from the [Kaggle Dogs vs. Cats competition](https://www.kaggle.com/c/dogs-vs-cats/data). It contains 25,000 images of cats and dogs, split evenly between the two classes. After downloading, extract the dataset into two folders: one for cats and one for dogs.

## Preprocessing

Preprocessing involves resizing images, normalizing pixel values, and encoding labels.

## Model Implementation

We will use `sklearn.svm.SVC` for the SVM classifier. The implementation includes standardizing the features, initializing the SVM classifier, and training the model.

## Results

Evaluate the performance of the trained SVM model on the test set, including calculating accuracy and generating a classification report.

## Visualization

Visualize the results using `matplotlib` and `seaborn`
### How to Use

To use this visualization:

1. Ensure you have `matplotlib` and `seaborn` installed in your Python environment.
2. Add the provided Python code block to your `train_svm.py` script or a separate visualization script.
3. Run the script after training your SVM model (`python train_svm.py`) to generate and display the confusion matrix heatmap.

## Conclusion

This project showcases the application of Support Vector Machines in image classification tasks. With proper preprocessing and feature extraction, SVMs can achieve impressive results even on complex datasets like Cats vs. Dogs.

## Installation

To run this project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/cats-vs-dogs-svm.git
    ```
2. Navigate to the project directory:
    ```bash
    cd cats-vs-dogs-svm
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Download the dataset from Kaggle and extract it into the project directory.
2. Update the paths to the cat and dog folders in the preprocessing script.
3. Install OpenCV if not already installed:
    ```bash
    pip install opencv-python
    ```
4. Run the preprocessing and training script:
    ```bash
    python train_svm.py
    ```
5. Evaluate the model and view the results.

## Contributing

We welcome contributions from the community. Please feel free to submit issues or pull requests to improve the project.
