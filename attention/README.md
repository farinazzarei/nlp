# Attention

In this project, we developed self-attention-based neural architecture inspired by the paper
[Attention Is All You Need](https://arxiv.org/pdf/1706.03762). Unlike traditional word embedding approaches the focus on
neighboring words, our implementation learns contextual relationships among all tokens within a sentence through the
attention mechanism. We used the **AG News dataset**, which contains 120,000 text samples categorized into four distinct
topics. the dataset was tokenized using the **bert-base-uncased** pretrained tokenizer. After tokenization positional encoding
was applied to preserve the sequential order of tokens. The transformer encoder block was then implemented from scratch,
incorporating multi-head self-attention and feed-forward layers as described in the original paper.
The model was trained on both the training and test datasets and its performance was evaluated using a confusion matrix
comparing the predicted and true labels for the four classes.


## requirements
[python](https://www.python.org/downloads/)

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install packages.

```bash
pip install numpy
pip install scikit-learn
pip install torch
pip install matplotlib

```

## how to run
To run this Jupyter Notebook, you can either open it in Google Colab using the link below or run it locally using Jupyter Notebook.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/farinazzarei/nlp/blob/main/attention/attention.ipynb)

Install Jupyter Notebook (if you don't have it yet):

```bash
pip install notebook
```
clone this repository :
```bash
git clone https://github.com/farinazzarei/nlp
cd nlp/attention
```
Launch Jupyter Notebook:
```bash
jupyter notebook
```
open the notebook file in your browser 
