# RO-animacy
## Background
This repository contains the code for a classifier that distinguishes between two classes of Romanian nouns: human and non-human. The classifier is built using pre-trained word embeddings and three different machine learning algorithms: Random Forest, Multi-layer Perceptron, and k-nearest neighbors. The corresponding paper is:
Tepei, M., & Bloem, J. (in press). **Automatic Animacy Classification for Romanian Nouns**. In *Proceedings of the Joint International Conference on Computational Linguistics, Language Resources and Evaluation 2024* (COLING-LREC 2024)
## Usage
Install the required libraries: nltk, gensim, numpy, pandas, scikit-learn, spacy.
Download the necessary data: 
- pre-trained word embeddings for Romanian (corola.300.20.vec): http://89.38.230.23/word_embeddings/
- SpaCy's Romanian model.
Execute the code in the notebook to preprocess data, train classifiers, and evaluate performance.
## Included files
- evaluation.txt: Input text file for evaluation (Wiki articles).
- noun_prediction_annotation.csv: Manually annotated labels and predicted labels.
