# SMS Spam Classification - Naive Bayes

This repository contains a project for SMS spam classification using the Naive Bayes algorithm.

## Required Libraries

The following libraries are required for this project:

- pathlib
- pandas
- numpy
- nltk
- sklearn
- seaborn
- ipywidgets
- imblearn

## Dataset

The dataset used in this project is `SMSSpamCollection`. Ensure the dataset is placed in the appropriate directory or update the `dataset_path` variable in the notebook.

## Steps

1. **Data Loading**: Load the dataset using pandas.
2. **Data Preprocessing**:
   - Remove stopwords
   - Lemmatize and stem words
   - Normalize and scale data
3. **Model Training**: Train a Naive Bayes classifier on the training set.
4. **Model Evaluation**: Evaluate the classifier using confusion matrix and accuracy score.

## Usage

Run the `Final_Update_NAIVEBAYES_SMSSPAM.ipynb` notebook to execute the project steps.

## Results

After running the notebook, you will get:
- The dataset size
- The first few rows of the dataset
- A count plot of the target variable
- The confusion matrix and accuracy score of the Naive Bayes classifier
- Interpretation of the confusion matrix

## Interpretation

- **True Positive (TP)**: Correctly predicted spam messages.
- **True Negative (TN)**: Correctly predicted non-spam messages.
- **False Positive (FP)**: Incorrectly predicted spam messages.
- **False Negative (FN)**: Incorrectly predicted non-spam messages.

## Example

To run the notebook, open it in Jupyter or Colab and execute the cells sequentially.

Ensure you have the required libraries installed and the dataset path updated in the notebook.
