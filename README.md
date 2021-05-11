# mnist_tutorial
A tutorial for MNIST handwritten digit classification using sklearn, PyTorch and Keras.

# Code structure
* [`numpy_matplotlib_sklearn.ipynb`](numpy_matplotlib_sklearn.ipynb): for numpy, matplotlib and sklearn.
* [`pytorch.ipynb`](pytorch.ipynb): for pytorch.
* [`keras.ipynb`](keras.ipynb): for keras.
* Reference solution: (not published yet)
    * [`numpy_matplotlib_sklearn_solution.ipynb`](numpy_matplotlib_sklearn_solution.ipynb)
    * [`pytorch_solution.ipynb`](pytorch_solution.ipynb)
    * [`keras_solution.ipynb`](keras_solution.ipynb)

# Requirements
Code tested on following environments, other version should also work:
* linux system (ubuntu 16.04) 
* python 3.6.3
* numpy 1.13.3
* matplotlib 2.1.0
* sklearn 0.19.1
* pytorch 0.4.1
* keras 2.1.2

# For students from SJTU
Please read [HEAR](EE369.md).

# Results of Experiments

|  Question  | Model  | Train_Acc | Test_Acc |
| :---------:|:------:|:--------:|:--------:|
| Q1 | LogisticRegression(defalt) | 97.20% | 87.90% |
| Q2 | BernoulliNB(default) | 81.63% | 81.90% |
| Q3 | LinearSVC(default) | 97.68% | 87.10% |
| Q4 | LinearSVC(adjusted) | 93.63% | 89.10%|
| Q5 | SimpleNet() | 99.36% | 98.95% |