# Sentiment Analysis

This repository contains a project for performing sentiment analysis on the IMDB movie reviews dataset using an LSTM model.

## Project Structure

- `LSTM_SENTIMENTAL_ANALYSIS_ON_IMDB.ipynb`: Jupyter notebook containing the code for data preprocessing, model training, and evaluation.
- `README.md`: Project documentation.
- `requirements.txt`: List of required Python packages.

## Table of Contents

- [Project Objective](#project-objective)
- [Installation Instructions](#installation-instructions)
- [Usage Instructions](#usage-instructions)
- [Model Architecture](#model-architecture)
- [Training the Model](#training-the-model)
- [Evaluation](#evaluation)
- [Results](#results)
- [License](#license)

## Project Objective

The objective of this project is to perform sentiment analysis on the IMDB movie reviews dataset using an LSTM model. The goal is to classify movie reviews as positive or negative based on their content.

## Installation Instructions

To install the required packages, run:
```bash
pip install -r requirements.txt
```

## Usage Instructions

1. Clone the repository:
```bash
git clone https://github.com/ChiefBibek/Sentiment_Analysis.git
```

2. Navigate to the project directory:
```bash
cd Sentimental_analysis
```

3. Install the required packages:
```bash
pip install -r requirements.txt
```

4. Open the Jupyter notebook and run the cells to preprocess the data, train the model, and evaluate its performance.

## Model Architecture

The model is built using an LSTM (Long Short-Term Memory) network. It includes an embedding layer, an LSTM layer, dropout layers, and dense layers to perform binary classification.

## Training the Model

The model is trained on the IMDB movie reviews dataset. The training process involves data preprocessing, tokenization, and the use of Word2Vec embeddings. The model is trained for a specified number of epochs with early stopping and model checkpointing.

## Evaluation

The model's performance is evaluated on a test dataset. Metrics such as accuracy, precision, recall, and F1-score are used to assess the model's performance. A confusion matrix is also generated to visualize the results.

## Results

The model achieves an accuracy of approximately 87% on the test data. Detailed performance metrics and visualizations are provided in the notebook.

## License

This project is licensed under the MIT License.

