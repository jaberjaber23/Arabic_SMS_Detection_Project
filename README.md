# Arabic SMS Project Detection
This project aims to detect and classify short text messages (SMS) written in Arabic. It utilizes machine learning techniques, including translation, pre-trained models, and deep learning algorithms, to achieve accurate classification results.

## Introduction
In today's digital age, the analysis and classification of text messages have become increasingly important. This project focuses specifically on Arabic SMS messages and provides a solution to automatically classify them based on their content.

## Translation using Google API
To ensure comprehensive coverage, the project incorporates the Google API for translation. This API seamlessly translates English text messages to Arabic, enabling the classification model to handle SMS messages in both languages effectively.

## Pre-trained Model: AraBERT
AraBERT, a powerful pre-trained transformer-based model designed for Arabic text, forms the core of this project. It serves as a foundation for understanding and analyzing Arabic language patterns, allowing accurate classification of SMS messages.

##Deep Learning Algorithms: CNN and LSTM
The project employs Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) networks, which are well-suited for text classification tasks. These deep learning algorithms excel at capturing essential features and patterns from SMS messages, enhancing the classification accuracy.

## Training and Evaluation
To train the classification models, a diverse dataset consisting of Arabic and translated English SMS messages was utilized. The dataset was meticulously labeled with appropriate class labels to enable supervised learning. The models were trained using a combination of AraBERT, CNN, and LSTM.

After training, the models were rigorously evaluated on a separate test dataset to measure their accuracy. Among the models, AraBERT emerged as the top performer, achieving an impressive test accuracy of 0.978515625. This outstanding accuracy highlights the model's ability to accurately classify Arabic SMS messages.

## GitHub Repository
The project's GitHub repository contains all the necessary code and resources to reproduce and utilize the Arabic SMS Project Detection. Here's an overview of the repository structure:

data_processing: This directory includes scripts and utilities for preprocessing the SMS data.
model_architecture: Here, you can find the implementation of the model architecture, including AraBERT, CNN, and LSTM.
training_scripts: This directory contains the scripts used for training the models on the dataset.
evaluation_metrics: Here, you will find the evaluation metrics used to assess the models' performance.
usage_examples: This directory provides examples and instructions on how to use the trained models for SMS classification.
Feel free to explore the repository and follow the step-by-step instructions to reproduce the results. The code is well-documented to facilitate understanding and ensure a smooth user experience.

## Conclusion
The Arabic SMS Project Detection is a cutting-edge project that leverages translation capabilities, pre-trained models, and deep learning algorithms to accurately classify SMS messages written in Arabic. The integration of AraBERT, along with CNN and LSTM architectures, enables the models to capture intricate language patterns and achieve exceptional accuracy. By providing an open-source solution, this project aims to contribute to the automation of SMS classification and benefit various applications in the Arabic-speaking community.
