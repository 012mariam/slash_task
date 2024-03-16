# slash_task
slash /Product Image Classifier
# Product Image Classifier

## Introduction
This task aims to develop a product image classifier using machine learning and deep learning technique. The classifier will categorize product images into predefined groups such as fashion,accessories,home,games , and stationary .

## Dataset
I have taken screenshots of product images obtained from [Slash-eg](https://slash-eg.com/) appplication . The images are categorized into different folders based on their respective product types.

## Data Preparation
- get the data at one dataframe has the image path and its label and this by looping to all folders and save its label 
- Image data is read and preprocessed using the `skimage` library.
- Images are resized to a (224,224) size to ensure consistency in input dimensions for the model.

## Building machine learning model
- Two machine learning models are explored: RandomForestClassifier and Support Vector Machine (SVM).

## Training
- The dataset is split into training and testing sets.
- with test_size=0.2

## Fine-Tuning
- Grid search is employed to find the best hyperparameters for the SVM model to get the best hyperparameters: {'C': 10, 'kernel': 'rbf'} for svm model.
## Building Deeplearning model 
We use a CNN architecture for image classification. The model consists of multiple convolutional layers followed by max-pooling layers for feature extraction. After flattening the output, we add dense layers for classification.





