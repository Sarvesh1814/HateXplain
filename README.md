# HateXplain AAAI 2021 Reproducibility Challenge 

This project is focused on classifying tweets into three groups: normal, hatespeech, and offensive. In addition to the main classification, the tweets are also classified into 21 subgroups representing the target community for the tweet. We have used two approaches for this task: classical machine learning models and deep learning models.

# Models Used
The classical machine learning models used for the task are:

**Logistic Regression**
-SVC

-Random Forest Classifier

-Naive Bayes Classifier

-Decision Tree Classifier

**The deep learning models used for the task are:**

-CNN_GRU
-BiRNN
-LSTM
-BERT

# Files
-Embeddings.ipynb: This file contains the methodology used to generate our own word2vec embeddings.
-HateXplain_Preprocessing.ipynb: This file includes the preprocessing of the HateXplain’s JSON data to convert it into useful form and saving the dataset into CSV format.
-Metadata.tsv: This file includes meta data for the embedding projections to understand the importance of all words using TensorFlow’s Embedding Projector.

# Usage
To use this project, you can clone this repository and run the various Jupyter notebooks included in the project. Each notebook contains the code for a different aspect of the project, from data preprocessing to model training and evaluation.


# Contributions:
-**Vipasha Vaghela**: HateXplain BiRNN, HateXplain BERT (Failed Attempt), Preprocessing  

-**Sarvesh Bagwe**:  Word2Vec Embeddings, LSTM with Glove Embeddings, CNN GRU HateXplain, Preprocessing

-**Vedant Dave**: Distill BERT HateXplain (Successful Attempt), CNN, Preprocessing 

-**Hiren Thakkar**: Classical Machine Learning Models, Preprocessing

Contributions to this project are welcome. Feel free to open an issue or submit a pull request with any improvements or suggestions.
