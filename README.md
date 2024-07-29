# Handwritten Digit Classification with SVD

This project uses Singular Value Decomposition (SVD) to classify handwritten digits, optimizing the number of singular vectors for better accuracy. It includes analyzing digit classification difficulty and enhancing image visualization for more precise recognition.

## Overview

Handwritten digit classification is an essential task in the field of pattern recognition and machine
learning. The ability to automatically recognize and classify handwritten digits has numerous
practical applications, such as optical character recognition, postal automation, and document
analysis. In this project, we present an algorithm for the classification of handwritten digits using
the Singular Value Decomposition (SVD) technique.

The primary objective of this project is to construct an algorithm that accurately classifies
handwritten digits based on a training set. The algorithm utilizes the SVD of each class matrix
and determines the optimal number of singular vectors to use as a basis for classification. We
measure the classification accuracy by considering the relative residual vector in the least squares
problem.

The specific tasks involved in this assignment are as follows:

1. **Tuning the algorithm for classification accuracy**:
We explore the relationship between the number of basis vectors used and the percentage of correctly classified digits. This analysis
helps determine the optimal number of basis vectors to achieve the highest classification accuracy.

2. **Assessing the difficulty of classifying digits**: We investigate whether all digits are equally
easy or difficult to classify. Additionally, we examine some of the difficult cases, noting that
poorly written digits pose challenges in classification.

3. **Analyzing the singular values of different classes**: We evaluate the singular values of the
classes and explore the possibility of using varying numbers of basis vectors for different
classes. Through experiments, we assess whether it is beneficial to utilize fewer basis vectors
for specific classes.

In addition to the required tasks, we will explore an optional two-stage
algorithm with SVD. This approach aims to optimize the test phase by comparing the unknown
digit only to the first singular vector in each class. We will analyze the effectiveness of this variant
and determine how frequently the second stage is unnecessary.
Moreover, we will enhance the image viewing capability by modifying the **ima2.m** function to
display 20 x 20 images.

In conclusion, this report presents an algorithm for handwritten digit classification using SVD.
Through experimentation and analysis, we aim to achieve accurate classification results while
exploring potential optimizations for the classification process.

## Dataset

The dataset provided consists of training and test data:
  - **dzip.txt** and **azip.txt**: These files contain the training data. **dzip.txt** holds the corresponding labels (digits), while **azip.txt** stores the training images represented as vectors.
  - **dtest.txt** and **testzip.txt**: These files contain the test data, with **dtest.txt** containing the labels and **testzip.txt** storing the test images.

### Additional Information

The repository also includes a `Report.pdf` that briefly explains our approach and methodology used to solve the problem.
