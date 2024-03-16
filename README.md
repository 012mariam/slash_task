# slash_task
slash /Product Image Classifier
# Product Image Classifier

## Introduction
This project aims to develop a product image classifier using machine learning techniques. The classifier will categorize product images into predefined groups such as fashion, nutrition, accessories, etc. The model can be useful for e-commerce platforms to automate the categorization of product images.

## Dataset
The dataset consists of product images obtained from [Slash-eg](https://slash-eg.com/). The images are categorized into different folders based on their respective product types.

## Data Preparation
- Image data is read and preprocessed using the `skimage` library.
- Images are resized to a uniform size to ensure consistency in input dimensions for the model.

## Model Building
- Two machine learning models are explored: RandomForestClassifier and Support Vector Machine (SVM).
- The RandomForestClassifier is trained using the `sklearn` library.
- SVM models with different kernels and hyperparameters are trained and evaluated.

## Training
- The dataset is split into training and testing sets using `train_test_split` from `sklearn.model_selection`.

## Validation
- Model performance is evaluated using accuracy, classification report, and confusion matrix.

## Fine-Tuning
- Grid search is employed to find the best hyperparameters for the SVM model using `GridSearchCV` from `sklearn.model_selection`.

## Testing
- The final model is tested on unseen data to evaluate its performance.

## Submission
- The trained model can be used for automated categorization of product images in e-commerce applications.

## Files Included
- `product_image_classifier.ipynb`: Jupyter notebook containing the code for data preprocessing, model building, training, validation, and testing.
- `README.md`: This file providing an overview of the project.
- `requirements.txt`: A list of Python packages required to run the code.
- `LICENSE`: License information for the project.

## Usage
1. Clone the repository: `git clone https://github.com/your-username/product-image-classifier.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Open and run the Jupyter notebook `product_image_classifier.ipynb` to reproduce the results.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

