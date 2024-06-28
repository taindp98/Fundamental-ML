# Mini-Project for Fundamentals of Machine Learning Course
![background](./materials/ai_wp.jpg)
This repository contains the code and data for a mini-project on facial expression recognition using machine learning algorithms.

## 📑 Project Policy
- Team: group should consist of 3-4 students.

    |No.| Student Name    | Student ID |
    | --------| -------- | ------- |
    |1|Phạm Gia Hy|21110311|
    |2|||
    |3|||
    |4|||

- The submission deadline is strict: **11:59 PM** on **June 22nd, 2024**. Commits pushed after this deadline will not be considered.

## 📦 Project Structure

The repository is organized into the following directories:

- **/data**: This directory contains the facial expression dataset. You'll need to download the dataset and place it here before running the notebooks. (Download link provided below)
- **/notebooks**: This directory contains the Jupyter notebook ```EDA.ipynb```. This notebook guides you through exploratory data analysis (EDA) and classification tasks.

## ⚙️ Usage

This project is designed to be completed in the following steps:

1. **Fork the Project**: Click on the ```Fork``` button on the top right corner of this repository, this will create a copy of the repository in your own GitHub account. Complete the table at the top by entering your team member names.

2. **Download the Dataset**: Download the facial expression dataset from the following [link](https://mega.nz/file/foM2wDaa#GPGyspdUB2WV-fATL-ZvYj3i4FqgbVKyct413gxg3rE) and place it in the **/data** directory:

3. **Complete the Tasks**: Open the ```notebooks/EDA.ipynb``` notebook in your Jupyter Notebook environment. The notebook is designed to guide you through various tasks, including:
    
    1. Prerequisite
    2. Principle Component Analysis
    3. Image Classification
    4. Evaluating Classification Performance 

    Make sure to run all the code cells in the ```EDA.ipynb``` notebook and ensure they produce output before committing and pushing your changes.

5. **Commit and Push Your Changes**: Once you've completed the tasks outlined in the notebook, commit your changes to your local repository and push them to your forked repository on GitHub.


Feel free to modify and extend the notebook to explore further aspects of the data and experiment with different algorithms. Good luck.

## Project Answer
Nội dung báo cáo:
1. Nội dung cần thiết đều nằm trong file notebook (EDA.ipynb), có thể không cần đọc file này cũng
được
2. Trong repo này, ta tiến hành thí nghiệm với 5 model trên tập dữ liệu icml_face_data.csv. Ta
apply cả 5 model vào dữ liệu đã qua xử lý PCA lẫn chưa qua xử lý PCA.
Các model:
a. K-nearest Neighbor

b. Gaussian Naïve Bayes

c. Random Forest

d. Multi-layer Perceptron

e. Convolutional Neural Network

3. Các kỹ thuật đã được áp dụng trong thí nghiệm này :
   
a. PCA

b. Data Augmentation

4. Model (Machine Learning) đạt được hiệu suất cao nhất trên tập dữ liệu gốc :
RandomForestClassifier() : 45.4%
Điểm chung giữa các model khi áp dụng vào data này: Class 5 lúc nào cũng đạt hiệu suất tốt nhất

• Class đạt hiệu suất tốt nhất : Class 5

• Class 0 và Class 4 luôn đạt hiệu suất thấp nhất

• Class 1 tuy có rất ít dữ liệu so với các Class còn lại, nhưng hiệu suất vẫn ổn định khi cho train
đủ lâu

• Precision cao nhất cũng là của class 5 (dùng RandomForestClassifier())
(với tập dữ liệu đã qua xử lý PCA) : 79%

6. Model (Deep Learning) CNN đạt hiệu suất 52% (metric: accuracy)
