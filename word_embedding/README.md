# Word Embedding

In this project, we implemented a word embedding model both manually and using the Gensim library.
In the manual method, we first created training data from a Persian text file.
This dataset consists of (context_word, center_word) pairs, where the context word is a neighbor of the center word within
a small window of a sentence. Then, we trained a model on this dataset.
The model, which has one hidden layer (the hidden layer represents the word embedding vector), predicts the neighbors of
an input word. we found similar words for a given word and also performed word analogy tasks between three words. 
In the second method, we used the Word2Vec Google News 300 dataset, which is a pretrained word-to-vector model consisting of approximately 3 million vectors (each vector has 300 dimensions).
Using this model, we implemented all the tasks mentioned above.
Finally, we created a simple neural network model with a binary output to predict positive or negative sentiment


## requirements
[python](https://www.python.org/downloads/)

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install packages.

```bash
pip install nltk
pip install gensim

```

## how to run
To run this Jupyter Notebook, you can either open it in Google Colab using the link below or run it locally using Jupyter Notebook.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/farinazzarei/nlp/blob/main/word_embedding/word%20embedding.ipynb)

Install Jupyter Notebook (if you don't have it yet):

```bash
pip install notebook
```
clone this repository :
```bash
git clone https://github.com/farinazzarei/nlp
cd nlp/word_embedding
```
Launch Jupyter Notebook:
```bash
jupyter notebook
```
open the notebook file in your browser 
