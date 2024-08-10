# Alphabet Soup Venture Funding Prediction
![image](https://github.com/user-attachments/assets/a67e8ca5-6122-42ad-bf9e-0c079014b1dc)
...
This repository contains the code and resources for building and optimizing a binary classification deep neural network model to predict whether startups funded by Alphabet Soup will be successful. The project involves data preprocessing, model compilation, evaluation, and optimization using TensorFlow and Keras.

## Project Overview

Alphabet Soup is a venture capital firm that receives many funding applications from startups daily. This project aims to build a predictive model using deep learning techniques to determine the likelihood of a startup's success if funded by Alphabet Soup.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Optimization](#model-optimization)
- [Results](#results)
- [License](#license)

## Dataset

The dataset used in this project contains information about over 34,000 organizations that have received funding from Alphabet Soup. Each row represents a startup, and the columns include various features such as funding amount, industry sector, and whether the startup was ultimately successful.

### Data Preprocessing

1. Dropped irrelevant columns (`EIN`, `NAME`).
2. Encoded categorical variables using `OneHotEncoder`.
3. Concatenated numerical variables with encoded categorical variables.
4. Split the data into features (`X`) and target (`y`).
5. Scaled the feature data using `StandardScaler`.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/AlphabetSoup-VentureFunding.git
    ```
2. Navigate to the project directory:
    ```bash
    cd AlphabetSoup-VentureFunding
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To train and evaluate the model:

1. Run the Jupyter notebook `AlphabetSoup_Model.ipynb` to preprocess the data, compile, and evaluate the neural network model.
2. The trained model will be saved as `AlphabetSoup.h5`.

To optimize the model:

1. Review the `AlphabetSoup_Optimization1.ipynb`, `AlphabetSoup_Optimization2.ipynb`, and `AlphabetSoup_Optimization3.ipynb` notebooks for different optimization attempts.
2. Each optimized model will be saved as `AlphabetSoup_Optimized1.h5`, `AlphabetSoup_Optimized2.h5`, and `AlphabetSoup_Optimized3.h5`.

## Model Optimization

Several optimization techniques were explored, including:

- Adjusting input features by dropping certain columns.
- Adding more neurons to hidden layers.
- Increasing the number of hidden layers.
- Trying different activation functions (`relu`, `sigmoid`, etc.).
- Varying the number of training epochs.

## Results

The results of each model, including accuracy and loss metrics, are compared to determine the best-performing model. Details can be found in the respective Jupyter notebooks.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

