<h1 align="center">Project 2 IF3170 Artificial Intelligence</h1>
<h1 align="center">Implementation of Machine Learning Algorithm</h1>

![GitHub last commit](https://img.shields.io/github/last-commit/Benardo07/Tubes-Ai-2)

## Overview

This project for IF3170 Artificial Intelligence focuses on implementing machine learning algorithms using the UNSW-NB15 dataset, which contains normal network activity and various types of cyberattacks. Participants are required to implement the following algorithms from scratch:

K-Nearest Neighbors (KNN): Support for adjustable parameters such as the number of neighbors and various distance metrics.
Gaussian Naive Bayes (GNB).
ID3 Decision Tree: Includes preprocessing for numerical data based on course material.
The project involves key stages such as data cleaning, transformation, feature selection, dimensionality reduction, modeling, validation, and result analysis. Participants must also compare their implementations with scikit-learn's library implementations. Additionally, models should be savable and reloadable.

As a bonus, participants can compete in a Kaggle competition to benchmark model performance on a leaderboard. The final submission includes a GitHub repository with source code, documentation, and comparisons of algorithm performance.
  
## Requirements

- **Python**
- **Pandas**
- **Scipy**
- **Scikit-Learn**
- **Matplotlib**
- **Numpy**
- **Pickle**

## How to Run the Program
### Step 1: Setup the program
To get started, you can clone the repository and run the application.

1. Clone the repository
```bash
git clone https://github.com/Benardo07/Tubes-Ai-2.git
``` 
2. Enter the directory
```
cd Tubes-Ai-2
```
### Step 2: Open the .ipynb file

1. Open the file with name IF3170 Artificial Intelligence _ Tugas Besar 2 Notebook Template (1).ipynb
2. Select your python kernel
3. Click Run all to run the file

## Additional
There are also pkl file for each of the model. For KNN, it is name knn_model.pkl. For naive bayess, it is name naive_model.pkl (make sure to use the pkl file, you need to pass numpy array). Lastly, for ID3 algorithm, it is in the file name id3_model.pkl
By using those pkl filem you can directly predict your dataset without training it again.

## Creator
| NIM      | Nama    | Pembagian Tugas |
| -------- | ------- | ----- |
| 13522019 | Wilson Yusda | KNN, Data Cleaning  |
| 13522021 | Filbert | ID3, Debugging  |
| 13522047 | Farel Winalda | ID3, ReadMe  |
| 13522055 | Benardo | Naive Bayes, Debugging  |
