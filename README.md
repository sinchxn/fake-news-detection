# Fake News Detection with Machine Learning

This project aims to build and evaluate various machine learning models for detecting fake news articles. The models are trained and tested on a dataset of news articles labeled as either "FAKE" or "REAL".

## Table of Contents

- [Dataset](#dataset)
- [Models](#models)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Dataset

The dataset used in this project is `train.csv`, which contains the following columns:

- `id`: Unique identifier for each news article
- `title`: Title of the news article
- `author`: Author of the news article
- `text`: Content of the news article
- `label`: Binary label indicating whether the article is "FAKE" (1) or "REAL" (0)

## Models

The following machine learning models are implemented and evaluated in this project:

1. **LSTM (Long Short-Term Memory)**: A deep learning model that uses recurrent neural networks to capture long-range dependencies in sequential data like text.
2. **Gradient Boosting**: An ensemble learning technique that combines multiple weak models (e.g., decision trees) in a gradual, additive manner.
3. **Decision Tree**: A tree-based model that makes decisions based on feature values.
4. **XGBoost**: An optimized gradient boosting algorithm that builds an ensemble of decision trees.
5. **Random Forest**: An ensemble learning method that constructs multiple decision trees and combines their outputs for improved performance.

## Installation

To run this project locally, follow these steps:

1. Clone the repository: git clone https://github.com/sinchxn/fake-news-detection.git
2. Install the following dependencies: pip install -r requirements.txt

## Usage

1. Make sure the `train.csv` dataset is present in the project directory.
2. Run the Jupyter Notebook `fake_news_detection.ipynb` to train and evaluate the models.
3. The notebook contains detailed code, explanations, and visualizations for each step of the process.

## Results

The performance of each model is evaluated using accuracy, confusion matrices, precision, recall, specificity, and F1-score. The results are presented in the Jupyter Notebook and can be used for comparison and analysis.

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Source
The data for this project was sourced from https://www.kaggle.com/competitions/fake-news/data?select=train.csv.

## License

This project is licensed under the [MIT License](LICENSE).
