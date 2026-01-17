Tabular-and-time-series

This repository collects three independent machine learning projects. Each project lives in its own directory with a notebook, its dependencies and a detailed README. The top‑level directory provides a short overview and links to the individual works.

Contents

Work 1 – Linear and ridge regression on California Housing with NumPy. This project demonstrates how to load tabular housing data, normalise it, and fit closed‑form linear and ridge regression models from scratch. It also explores the effect of the regularisation parameter on the model’s error.

Work 2 – Single‑layer neural network on MNIST with NumPy. Using only NumPy, this project implements a one‑hidden‑layer feedforward network to recognise handwritten digits from the MNIST dataset. It includes an efficient one‑hot encoder, a sigmoid activation function, and training via backpropagation.

Work 3 – Time‑series classification on UCR/UEA datasets. This project compares several deep‑learning and classical approaches (fully connected networks, 1D CNNs, RNNs, Rocket, ResNet, TapNet, KNN with feature transforms) on multiple univariate and multivariate time‑series datasets from the UCR/UEA archive. A PDF report summarises the results.

Each subfolder contains its own requirements.txt and README.md files with installation and run instructions. To work with a particular project, change into the corresponding directory and follow the steps described there.
