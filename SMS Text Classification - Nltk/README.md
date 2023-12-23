# SMS Text Classification
Everyday we receives many different sms and it is hard to detect whether it is real or fake and due to such fake messages many scam are done.To prevent such scams I have create this sms text classification
This projects focuses on detecting spam or ham messages using nltk and Neural Network. The model is trained on dataset containg spam and ham messages, and Regular expression technique have been applied to improve the model by cleaning the dataset.

## Requirements

- Google Colaboratory account/Jupyter Notebook
- Understanding of Python, TensorFlow, Keras, Nltk and Regexs

## Installation

1. Download the .ipynb file.

2. Upload the file to your drive and open it as a google colab file or use jupyter notebook

## Dataset

To get the dataset the code is already written in the notebook you just have to run the cell and it will autmatically load the dataset.

## Preparing Data
First we will remove the stop words from the nltk stopwords for english.Then we use regex to remove extra spaces and then WordNetLematizer to convert the words and then tokenize the words.

## Model Architecture

The Neural Networks architecture is defined within the Colab notebook. Look for the code cells related to model architecture to understand the layers and structure.

## Training

Follow the training steps outlined in the Colab notebook. Execute the cells related to model training to initiate the training process.

## Evaluation

Evaluate the model on a test set using the evaluation cells provided in the Colab notebook.


## Contributing

If you'd like to contribute to this project, please feel free to open an issue or submit a pull request in this GitHub repository.


