# PyTorch Intro

PyTorch development notebook based on IBM lecture

See [misc/ibm](misc/ibm/) for their notebooks, or the root directory for my notebooks.

## How to Use

1. Create a Python [virtual environment](https://code.visualstudio.com/docs/python/environments) first if necessary
2. To install PyTorch, refer to [this link](https://pytorch.org/get-started/locally/). I'm using this one for Python 3.12 and CUDA 12.4:
    ```
    pip install torch==2.4.1 torchvision==0.19.1 --index-url https://download.pytorch.org/whl/cu124
    ```
3. Install other required libraries using `pip install -r requirements.txt`
4. Open the notebook (`ipynb`) file

## Misc

Inspired from:
- https://github.com/fchollet/deep-learning-with-python-notebooks
- https://github.com/fastai/fastai_old/tree/master/dev_nb (and their book)