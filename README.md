# Cat vs. Dog Identification using Deep Learning

Welcome to the Cat vs. Dog Identification using Deep Learning GitHub repository! This project focuses on building a deep learning model to classify images as either cat or dog. The repository contains the necessary code and resources for training and evaluating the model.

## Repository Contents

1. **AI**: This folder contains the dataset, consisting of 500 images in total, with 250 images for each class (cat and dog). The dataset is balanced, ensuring an equal representation of both classes.

2. **Graph**: In this folder, you will find graphs generated from k-fold cross-validation runs. These graphs provide insights into the model's performance across different folds.

3. **FinalSubmission.ipynb**: This Jupyter Notebook file encapsulates the final model implementation. The notebook includes code for data augmentation, k-fold cross-validation, and model training. The classes are labeled as follows: 0 for cat and 1 for dog.

## Project Details

- **Dataset**: The dataset is carefully curated with 250 images for each class, ensuring a balanced representation of cats and dogs.

- **Data Augmentation**: The dataset has been augmented to enhance the diversity of training examples, which is crucial for building a robust model.

- **Data Split**: The dataset is split into training and testing sets with an 80/20 ratio, ensuring a reliable evaluation of the model's performance.

- **Training Parameters**:
  - Learning Rate: 0.01
  - Momentum: 0.9
  - Epochs: 100

## How to Use

1. Navigate to the `FinalSubmission.ipynb` file.

2. Open the Colab and upload the notebook to explore the implementation of the model.

3. Run the notebook cell by cell to understand the training process, data augmentation, and model evaluation.

Feel free to experiment with the code, and if you have any questions, feedback, or issues, please don't hesitate to reach out. Happy classifying cats and dogs!
