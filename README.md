# DBNLDA
Deep Belief Network based representation learning for LncRNA-Disease association prediction

DBNLDA is a deep belief network based model for predicting potential Long non-coding RNA (lncRNA) disease association. LncRNAs are non-coding RNAs having length greater than 200 nucleotides. Researches identified abnormal expression of lncRNAs in complex diseases including cancers, heart failure and alzheimer's disease. Computationally predicting lncRNA-disease association have vital role in understanding lncRNA functionalities and dieseas mechanism. 

Project Home Page: http://bdbl.nitc.ac.in/dbnlda/index.html

## Packages Required
* Networkx
* Node2Vec
* TensorFlow 1.5 or above
* PyTorch
* Scikit Learn
* Numpy
* Pandas

This repository contains:
1. dataset: datasets in csv and xls format
2. code: Python implementation files for DBNLDA
      1. Network_creation.ipynb - Jupyter notebook for creating LMS, DMS and LDA networks
      1. DBN_learning.ipynb - Jupyter notebook for DBN based representation of lncRNA, disease pairs
      1. NNClassifier-CV.ipynb- Jupyter notebook for running neural network based classification and cross validation

The notebook files have to be run in the following sequence:
1. Network_creation.ipynb
2. DBN_learning.ipynb
3. NNClassifier-CV.ipynb
