Cancer Detection Model
This repository contains the code for a machine learning model designed to detect cancer from a dataset. The model uses TensorFlow and Keras to build and train a neural network. The dataset used is from a CSV file named cancer.csv.

Project Overview
The goal of this project is to create a binary classifier that can distinguish between malignant (m) and benign (b) tumors based on various features. The model uses a feedforward neural network with two hidden layers.

Dependencies
To run this project, you need to have Python and the following libraries installed:

pandas
numpy
scikit-learn
tensorflow
You can install the required libraries using pip:

bash
Copy code
pip install pandas numpy scikit-learn tensorflow
Dataset
The dataset cancer.csv should contain the following columns:

Features: Various measurements of the tumor.
diagnosis(1=m, 0=b): Target variable indicating whether the tumor is malignant (1) or benign (0).
