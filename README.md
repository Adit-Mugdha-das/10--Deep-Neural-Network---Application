# Deep Neural Network – Cat vs Non-Cat Classifier 

This  is an application of a deep L-layer neural network to classify images as cats or non-cats.  
It is the final assignment of **Week 4 (Course 1: Neural Networks and Deep Learning)** from the **Deep Learning Specialization** by Andrew Ng on Coursera.

##  Project Overview

This project brings together everything covered in Course 1 and applies it to a real-world task: **binary image classification** using a deep neural network. The dataset consists of 64x64 RGB images, and the network is trained to predict whether an image contains a cat.

##  What I Implemented

- A complete deep L-layer neural network using NumPy
- Forward propagation (Linear → Activation → Linear → Activation...)
- Cost computation with cross-entropy loss
- Backward propagation for gradients
- Parameters update using gradient descent
- Preprocessing of image data (flattening, normalization)
- Prediction function to test new images
- Visualization of misclassified examples

##  Folder Contents

- `deep_nn_app.ipynb` – Main notebook with all code and explanations
- `dataset/` – Training/test image data (X, Y)
- `testCases_v4b.py` – Test functions to validate correctness
- `dnn_app_utils_v3.py` – Utility functions for the deep model
- `images/` – Contains image samples for prediction

##  Technologies Used

- Python 3
- NumPy
- Matplotlib
- h5py (for dataset loading)

##  Course Info

This project is part of:
> [Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning)  
> Instructor: **Andrew Ng**

##  Honor Code Notice

This repository contains **only my own code and insights**. It does not include any auto-graded or proprietary content from Coursera. It follows the Honor Code and is intended for learning and portfolio purposes only.

---

 If you're also exploring deep learning, feel free to fork or star the repo!
