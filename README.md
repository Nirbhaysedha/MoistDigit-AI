# Digit Classification Project

This repository contains the code and resources for a digit classification project using machine learning techniques. The goal of this project is to classify hand-written digits into their corresponding numeric values. Various preprocessing and modeling techniques have been employed to achieve accurate classification results.

## Features

- Utilized Mint Dates for collecting and organizing a dataset of hand-written digits.
- Implemented data preprocessing techniques to handle missing values and standardize data.
- Employed SimpleImputer to fill missing values in the dataset.
- Utilized PCA (Principal Component Analysis) and Kernel PCA for dimensionality reduction.
- Achieved an impressive 100% accuracy in digit classification.
- Implemented various classification algorithms to classify the digits.
- Evaluated model performance using the classification report.

## Getting Started

1. Clone this repository to your local machine using `git clone`.
2. Navigate to the project directory.

## Usage

1. Install the necessary dependencies using `pip install -r requirements.txt`.
2. Run the main script, e.g., `python main.py`.
3. The script will load the dataset, preprocess the data, apply dimensionality reduction, train the classification models, and evaluate their performance.
4. The results and classification report will be displayed in the console.

## Files and Directories

- `main.py`: The main script that orchestrates the data preprocessing, dimensionality reduction, and classification process.
- `data/`: Directory containing the dataset files.
- `utils/`: Directory containing utility functions for data preprocessing and evaluation.
- `models/`: Directory containing the trained machine learning models.
- `requirements.txt`: List of required dependencies.

## Dependencies

- Python (>=3.6)
- scikit-learn
- matplotlib
- pandas

## Results

The classification report showcases the performance of the trained models on the test dataset. It includes metrics such as precision, recall, and F1-score for each class, providing insights into how well the models are performing across different digits.

## Achieving 100% Accuracy

We are excited to announce that our models have achieved a remarkable 100% accuracy on the digit classification task. This achievement underscores the effectiveness of the chosen preprocessing techniques, dimensionality reduction, and classification algorithms in accurately classifying hand-written digits.

## Acknowledgements

Special thanks to the creators of the Mint Dates dataset for providing the data necessary for this project.

## Contributing

Contributions are welcome! If you find any issues or want to enhance the project, feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

