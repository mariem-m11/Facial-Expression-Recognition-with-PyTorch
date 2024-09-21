# Facial Expression Recognition

## Overview
This project utilizes a deep learning approach to recognize and classify facial expressions from images into seven categories: angry, disgust, fear, happy, neutral, sad, and surprise. I used a pre-trained EfficientNet B0 model adapted for this classification task.

## Model Architecture
The core of this project is the EfficientNet B0 model, which has been fine-tuned to classify facial expressions. The model was chosen for its efficiency and effectiveness in handling image classification tasks with a relatively low computational cost. Modifications include adjusting the final layers to output seven classes and training on a specialized dataset of facial expressions.

## Data
The dataset comprises images labeled across seven facial expression categories and is available on Kaggle. It has been split into training and validation sets to ensure the model generalizes well to new data.

- **Dataset source:** [Face Expression Recognition Dataset](https://www.kaggle.com/jonathanoheix/face-expression-recognition-dataset)
