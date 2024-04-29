# Cat Recognition Deep Learning Project
This repository contains a deep learning project for recognizing different types of cats in images using Keras and TensorFlow. The project involves various stages including data preprocessing, model training, evaluation, and prediction.

## Project Overview
The project consists of the following main components:

1. Data Collection: Initially, a dataset containing images of five types of cats (cat, lion, tiger, cheetah, and leopard) was collected from various sources.
Exploratory Data Analysis (EDA): An exploratory data analysis was performed to gain insights into the dataset. This involved analyzing the distribution of images among different categories, visualizing sample images, and identifying any data imbalances.

2. Data Preprocessing: Before training the deep learning models, the dataset was preprocessed. This included tasks such as resizing images, splitting the data into training, validation, and test sets, and performing data augmentation techniques to increase the diversity of the training data.
   
3. Model Selection and Training: Ten different deep learning models were experimented with, including pre-trained models such as Xception, ResNet, Inception, and MobileNet. Transfer learning was applied by fine-tuning these pre-trained models on the cat dataset. The models were trained on the augmented training data and their performance was evaluated using the validation set.
   
4. Model Evaluation: The trained models were evaluated using various metrics such as accuracy, loss, and confusion matrix. This helped in assessing the performance of each model and selecting the best-performing one for deployment.
   
5. Prediction: Finally, the selected model was used to make predictions on a separate test dataset. The predictions were saved to a CSV file for further analysis.

## Getting Started
To run this project locally, follow these steps:

1. Clone this repository to your local machine.
2. Explore the Jupyter notebook to understand the project workflow and analysis.
3. Train the deep learning models using the provided notebooks.
4. Evaluate the trained models and make predictions on the test data.
   
