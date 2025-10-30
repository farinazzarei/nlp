# Word Embedding

In this project, we implemented a neural network using the PyTorch library on the **EMNIST** dataset. This dataset is a
collection of lowercase and uppercase alphabets as well as numbers. We split the dataset into training, validation,
and test sets. We started with a simple neural network trained using the SGD optimizer, but the loss and accuracy on both
the training and validation sets were not satisfactory. Next, we switched to the Adam optimizer, which produced better
results; however, the gap between training and validation performance indicated overfitting. To address this, we trained
a deeper network and added batch normalization, which improved the training loss and accuracy but did not fully resolve
the overfitting issue. To further combat overfitting, we applied dropout to every layer. Initially, this led to underfitting
until around the 10th epoch, after which the network’s performance improved.


## requirements
[python](https://www.python.org/downloads/)

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install packages.

```bash
pip install torch
pip install scikit-learn
pip install matplotlib
pip install medmnist
```

## how to run
To run this Jupyter Notebook, you can either open it in Google Colab using the link below or run it locally using Jupyter Notebook.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/farinazzarei/nn_projects/blob/main/improving_nns/improving_nns.ipynb)

Install Jupyter Notebook (if you don't have it yet):

```bash
pip install notebook
```
clone this repository :
```bash
git clone https://github.com/farinazzarei/nn_projects.git
cd nn_projects/improving_nns
```
Launch Jupyter Notebook:
```bash
jupyter notebook
```
open the notebook file in your browser 
