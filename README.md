# MINI PROJECT FUNDAMENTAL ML - Nhóm 4CE

> [!IMPORTANT]
> In this project, we aim to classify images by first using **Principal Component Analysis (PCA)** for dimensionality reduction. PCA helps in transforming the images into a lower-dimensional space while preserving as much variance as possible. After the dimensionality reduction, we will classify the images using a Machine Learning Model, specifically a **Multi-Layer Perceptron (MLP)**. Additionally, we plan to explore **Convolutional Neural Networks (CNN), Histogram of Oriented Gradients (HOG)** as further work.

> [!NOTE]
> You can go to the url https://thangbuiq.github.io/NMMH-4CE for easily view of this file.

## Team Members

| Name               | Student ID | Responsibilities                                                                                   |
|--------------------|------------|----------------------------------------------------------------------------------------------------|
| Bui Quang Thang    | 21280048   | Leader, ensure timely completion, integrating all parts of the project and compiling the final report |
| Le Vo Bao Tram     | 21280052   | Handle EDA for each label, apply XgBoost, MLP, and Naive Bayes classification                     |
| Huynh Thi Thu Thoang | 21280074  | Apply Random Forest, MLP classification, and compare before and after PCA performance              |
| Nguyen Thuy Vy     | 21280120   | GridSearchCV to DecisionTree as e.g, implement model pipeline and handle SVM classification        |

## Methodology tl;dr

- Feature Engineering: PCA to reduce the dimensionality while preserving variance (95% cut-off)
- Core ML Algos: Multi-Layer Perceptron (MLP), Random Forest, XgBoost, Naive,... and PCA comparison
- Further work: Convolutional Neural Networks (CNN) for improved classification accuracy

## Project Structure

The repository is organized into the following directories:

- **/data**: This directory contains the facial expression dataset. You'll need to download the dataset and place it here before running the notebooks.
- **/notebooks**: This directory contains the Jupyter notebook ```EDA.ipynb```. This notebook guides you through exploratory data analysis (EDA) and classification tasks.
