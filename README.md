# Signature Verification Using Visual Analytics

This repository contains the Python code for a signature verification system using visual analytics techniques. The system is designed to classify signatures as genuine or forged.

## Workflow

The code performs the following steps:

### 1) Preprocessing: 

    - Reads images of genuine and forged signatures from directories.
    - Converts the images to grayscale.
    - Resizes the images to a uniform size.

### 2) Feature Extraction:

Applies various image processing techniques to extract features from the images, including:

    - Gaussian blur to reduce noise.
    - Canny edge detection to detect edges.
    - Dilation to thicken the edges.
    - Thresholding to create binary images.
    - Hough circle transform to detect circles.
    - Hough line transform to detect lines.
    - Finding contours in the binary images.

### 3) Classification:

    - Trains a Random Forest classifier to distinguish between genuine and forged signatures based on the extracted features.
    - Evaluates the performance of the classifier using metrics such as accuracy, precision, recall, and F1 score.

## Instructions

To run the code, you will need the following libraries:

    - OpenCV
    - NumPy
    - scikit-learn
    - matplotlib

Once you have installed the libraries, you can run the code by following these steps:

    1) Clone the repository.
    2) Navigate to the repository directory.
    3) Execute the Python script (e.g., python signature_verification.py).

## Data

    The code assumes that you have two directories containing grayscale images of genuine and forged signatures. The directory paths are hardcoded in the script. You will need to modify these paths to point to your own data directories.

## Evaluation

    The code prints the following evaluation metrics:

    - Accuracy score
    - Precision score
    - Recall score
    - F1 score
    
    The code also plots a confusion matrix and a bar chart showing the precision, recall, and F1 scores.

## Future Work

    This is a basic implementation of a signature verification system. Potential areas for future work include:

    - Experimenting with different feature extraction techniques.
    - Trying different machine learning algorithms for classification.
    - Implementing a user interface for the system.

I hope this Readme.md file provides a clear understanding of the purpose and functionality of the code.
## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://linktr.ee/rafi.ansari)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rafi-ansari/)

