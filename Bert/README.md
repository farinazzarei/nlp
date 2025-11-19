# Attention

In this project, we implemented the BERT algorithm on the **IMDB** dataset, which consists of 50,000 movie reviews commonly
used for text sentiment analysis. First, we used the **bert-base-uncased** model to tokenize the data and train a
**BertForSequenceClassification** model, which is based on the Transformer architecture for text classification. Finally,
we evaluated the model using scikit-learn metrics and a confusion matrix, and also trained the model on our own small 
dataset to demonstrate sentiment analysis performance.

## requirements
[python](https://www.python.org/downloads/)

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install packages.


## how to run
To run this Jupyter Notebook, you can either open it in Google Colab using the link below or run it locally using Jupyter Notebook.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/farinazzarei/nlp/blob/main/bert/bert.ipynb)

Install Jupyter Notebook (if you don't have it yet):

```bash
pip install notebook
```
clone this repository :
```bash
git clone https://github.com/farinazzarei/nlp
cd nlp/bert
```
Launch Jupyter Notebook:
```bash
jupyter notebook
```
open the notebook file in your browser 
