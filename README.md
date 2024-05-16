# Alphabet Soup Funding Prediction Project

## Overview
This project aims to develop a binary classification model to predict the success of applicants if funded by Alphabet Soup, a nonprofit organization. The model utilizes deep learning techniques to analyze various features of past applicants and predict their likelihood of success.

## Project Structure
- `Starter_Code.ipynb`: Jupyter Notebook containing the initial data preprocessing, model development, and evaluation.
- `AlphabetSoupCharity_Optimisation.ipynb`: Jupyter Notebook focusing on model optimization to achieve target performance.
- `charity_data.csv`: Dataset containing information about past applicants.
- `AlphabetSoupCharity.h5`: Saved model file from the initial model development.
- `AlphabetSoupCharity_Optimisation.h5`: Saved model file from the optimized model.

## Project Workflow
1. **Data Preprocessing:** 
   - Analyze and preprocess the dataset by dropping irrelevant columns and encoding categorical variables.
   - Split the data into training and testing sets.

2. **Model Development:**
   - Build a neural network model using TensorFlow and Keras.
   - Compile, train, and evaluate the model on the training and testing data.

3. **Model Optimization:**
   - Experiment with different model architectures, activation functions, and hyperparameters to improve performance.
   - Save the optimized model for future use.

## Results
- The initial model achieved moderate accuracy but fell short of the target performance threshold.
- Through optimization efforts, the model accuracy was improved to over 75%, meeting the project's objective.
- Different strategies were employed, including adjusting the neural network structure, exploring alternative activation functions, and fine-tuning hyperparameters.

## Conclusion
The developed model demonstrates promising results in predicting the success of applicants if funded by Alphabet Soup. By leveraging deep learning techniques and continuous optimization efforts, the model can assist Alphabet Soup in selecting applicants with the highest likelihood of success for funding.
