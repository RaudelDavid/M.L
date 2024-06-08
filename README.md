
Malaria Cell Detection Pipeline

This repository contains a comprehensive pipeline for training a Convolutional Neural Network (CNN) to distinguish between malaria-infected and uninfected cells. The project utilizes an automated hyperparameter tuner to optimize the architecture and improve accuracy.

Overview
The goal of this project is to develop a robust model that can accurately identify malaria-infected cells from microscopic images. By leveraging advanced deep learning techniques, we aim to enhance the precision and efficiency of malaria diagnosis.

Features
CNN Architecture: Utilizes a state-of-the-art Convolutional Neural Network to process and classify cell images.
Automated Hyperparameter Tuning: Employs an auto-tuner to fine-tune the model architecture and hyperparameters for optimal performance.
High Accuracy: Achieves high accuracy in distinguishing between infected and uninfected cells.
Installation
To run this project, you will need to have the following dependencies installed:

Python 3.7+
TensorFlow
Keras
AutoKeras
Jupyter Notebook


Dataset
The dataset used for this project consists of microscopic images of blood cells, with labels indicating whether each cell is infected with malaria or not. You can download the dataset from:

https://storage.googleapis.com/platzi-tf2/MalariaCells.zip \ 
	-O /tmp/MalariaCells.zip

Model Training
The notebook provides a step-by-step guide to training the CNN model. It includes:

Data Preprocessing: Normalizes and augments the image data to improve model robustness.
Model Definition: Defines the CNN architecture using Keras.
Hyperparameter Tuning: Utilizes AutoKeras to find the best hyperparameters.
Model Training: Trains the model on the preprocessed data.
Evaluation: Assesses the model's performance on a test set.
Results
The trained model achieves high accuracy in classifying malaria-infected and uninfected cells. Detailed results and performance metrics are provided in the notebook.

Contributing
We welcome contributions to improve the project. Please fork the repository and create a pull request with your changes.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
The dataset used in this project was provided by [Data Source].
Special thanks to the contributors of TensorFlow, Keras, and AutoKeras.

