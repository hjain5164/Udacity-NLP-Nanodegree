## Introduction to the Project

LDA is used to classify text in a document to a particular topic. It builds a topic per document model and words per topic model, modeled as Dirichlet distributions.
* Each document is modeled as a multinomial distribution of topics and each topic is modeled as a multinomial distribution of words.
* LDA assumes that the every chunk of text we feed into it will contain words that are somehow related. Therefore choosing the right corpus of data is crucial.
* It also assumes documents are produced from a mixture of topics. Those topics then generate words based on their probability distribution.

## Installation
You require following modules to run the [notebook](https://github.com/hjain5164/Udacity-NLP-Nanodegree/blob/master/Topic%20Modeling%20-%20Project%20Work-3/Solution%20-%20Latent_dirichlet_allocation.ipynb):
* pandas
* gensim
* nltk
