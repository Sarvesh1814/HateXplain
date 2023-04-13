# **HateXplain**

This repository contains code for the HateXplain project which aims to classify hate speech and offensive language in text.

# **Embeddings**
The Embeddings.ipynb file in this repository contains code to create Word2Vec embeddings for the dataset and visualize the words using the Embedding Projector, which helps to gain a better understanding of the dataset.

# **Models Created**

We have implemented several models for hate speech classification, including:

1) **LSTM** - basic LSTM architecture was used for classification but it didn't perform well on validation data.
2) **LSTM Custom Loss** - modified the loss to mask cross entropy to justify the decision making, but still didn't see any improvement in the model.
3) **LSTM Glove** - used pre-trained glove embeddings and fine-tuned on our dataset, resulting in a 52% validation accuracy (compared to the paper's model accuracy of 69%).
4) **CNN_GRU models** - 5 different versions of the model were created with various tweaks and capacity changes. The best performance was achieved on the **CNN_GRU_V5** model, which had less overfitting compared to the LSTM Glove model.

5) **CNN_GRU models** - from version 6 we started working on combined out of text class and the target community by the use of CNN_GRU models
  CNN_GRU_V6 : https://colab.research.google.com/drive/154WXNkakCuT4iErIjd02Fo7R5dZvCR4E?usp=sharing
  
  CNN_GRU_V7 : https://colab.research.google.com/drive/1m4qh51M050d9l2XK-urWqjvJNC71kmNR?usp=sharing

We continue to work on improving the models for hate speech classification and welcome contributions from the community.
