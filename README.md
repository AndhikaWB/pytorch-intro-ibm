# PyTorch Intro

PyTorch development notebook based on IBM lecture

See [misc/ibm](misc/ibm/) for their notebooks, or the root directory for my notebooks

List of my notebooks (WIP):
1. [Linear regression](1_linear_regression.ipynb)

    Linear regression (simple & multiple), gradient descent (batch & stochastic), PyTorch intro such as tensor, dataset, and module

2. Logistic regression

    Similar to linear regression but for classification task

3. ANN

    Simple linear network

4. CNN

    More complex neural network

5. LSTM

    Uncovered by IBM. Todo if possible

## Setup

1. Create a Python [virtual environment](https://code.visualstudio.com/docs/python/environments) first if necessary
2. To install PyTorch, refer to [this link](https://pytorch.org/get-started/locally/). For example, for Python 3.12 and CUDA 12.4 you should use:

    ```
    pip install torch==2.4.1 torchvision==0.19.1 --index-url https://download.pytorch.org/whl/cu124
    ```
    
3. Install other required libraries using `pip install -r requirements.txt`
4. Open the notebook (`ipynb`) file that you want

## Misc

Dataset used:

- https://www.kaggle.com/datasets/harrimansaragih/dummy-advertising-and-sales-data

Inspired by similar repos:

- https://github.com/fchollet/deep-learning-with-python-notebooks
- https://github.com/fastai/fastai_old/tree/master/dev_nb (and their book)