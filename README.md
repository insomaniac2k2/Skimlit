# Skimlit
Abstract Classification with Medical Text
This repository contains code and models for classifying sentences from medical abstracts into different categories. The categories include 'BACKGROUND', 'CONCLUSIONS', 'METHODS', 'OBJECTIVE', and 'RESULTS'. The best-performing model among the five created models is the Tribrid Model, which utilizes a combination of token, position, and character embeddings.

Dataset
The dataset used for training and evaluation consists of medical abstracts with annotated sentence-level labels. Each sentence in the dataset is labeled with one of the five categories mentioned above. The dataset was preprocessed and split into training, validation, and test sets.

Model Architecture
The Tribrid Model is a deep learning model that combines token embeddings, position embeddings, and character embeddings to capture both semantic and positional information. The architecture of the model includes several layers of neural networks, including recurrent or convolutional layers, followed by fully connected layers for classification. The model was trained using a supervised learning approach with cross-entropy loss.

Dependencies
To run the code and use the models, the following dependencies need to be installed:

* Python (version 3.11.X)
* TensorFlow (version 2.12.X)
* NumPy (version 1.24.X)
* Pandas (version 2.0.X)
