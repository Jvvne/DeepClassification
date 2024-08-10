# DeepClassification

Alphabet Soup Venture Funding Prediction
This repository contains the code and resources for building and optimizing a binary classification deep neural network model to predict whether startups funded by Alphabet Soup will be successful. The project involves data preprocessing, model compilation, evaluation, and optimization using TensorFlow and Keras.

Project Overview
Alphabet Soup is a venture capital firm that receives many funding applications from startups daily. This project aims to build a predictive model using deep learning techniques to determine the likelihood of a startup's success if funded by Alphabet Soup.

Table of Contents
Project Overview
Dataset
Installation
Usage
Model Optimization
Results
License
Dataset
The dataset used in this project contains information about over 34,000 organizations that have received funding from Alphabet Soup. Each row represents a startup, and the columns include various features such as funding amount, industry sector, and whether the startup was ultimately successful.

Data Preprocessing
Dropped irrelevant columns (EIN, NAME).
Encoded categorical variables using OneHotEncoder.
Concatenated numerical variables with encoded categorical variables.
Split the data into features (X) and target (y).
Scaled the feature data using StandardScaler.
Installation
To run this project locally, follow these steps:

Clone the repository:
bash
Copy code
git clone https://github.com/your-username/AlphabetSoup-VentureFunding.git
Navigate to the project directory:
bash
Copy code
cd AlphabetSoup-VentureFunding
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Usage
To train and evaluate the model:

Run the Jupyter notebook AlphabetSoup_Model.ipynb to preprocess the data, compile, and evaluate the neural network model.
The trained model will be saved as AlphabetSoup.h5.
To optimize the model:

Review the AlphabetSoup_Optimization1.ipynb, AlphabetSoup_Optimization2.ipynb, and AlphabetSoup_Optimization3.ipynb notebooks for different optimization attempts.
Each optimized model will be saved as AlphabetSoup_Optimized1.h5, AlphabetSoup_Optimized2.h5, and AlphabetSoup_Optimized3.h5.
Model Optimization
Several optimization techniques were explored, including:

Adjusting input features by dropping certain columns.
Adding more neurons to hidden layers.
Increasing the number of hidden layers.
Trying different activation functions (relu, sigmoid, etc.).
Varying the number of training epochs.
Results
The results of each model, including accuracy and loss metrics, are compared to determine the best-performing model. Details can be found in the respective Jupyter notebooks.
