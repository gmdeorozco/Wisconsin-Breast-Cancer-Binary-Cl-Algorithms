# Binary Classification Algorithms Comparison

![Binary Classification](https://img.shields.io/badge/Binary%20Classification-Algorithms%20Comparison-blue)

This GitHub repository provides a comprehensive comparison of various binary classification algorithms using the well-known Breast Cancer Wisconsin dataset. The goal of this project is to assess the performance and characteristics of different algorithms when applied to the task of classifying breast cancer as malignant or benign.

## Dataset - Breast Cancer Wisconsin

The [Breast Cancer Wisconsin](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29) dataset is a widely used dataset for binary classification tasks in machine learning. It contains features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. The features describe the characteristics of cell nuclei present in the image.

## Algorithms Compared

The following binary classification algorithms are compared in this project:

1. Logistic Regression
2. k-Nearest Neighbors (k-NN)
3. Support Vector Machine (SVM)
4. Decision Tree
5. Random Forest
6. Gradient Boosting
7. Naive Bayes
8. Neural Network

## Evaluation Metrics

To assess the performance of each algorithm, the following evaluation metrics are used:

- Accuracy
- Precision
- Recall (Sensitivity)
- F1 Score
- ROC AUC

## Project Structure

```
- data/
  - breast_cancer_wisconsin.csv    # Breast Cancer Wisconsin dataset
- notebooks/
  - data_exploration.ipynb         # Data exploration notebook
  - algorithm_comparison.ipynb     # Algorithm comparison notebook
- src/
  - data_preprocessing.py          # Data preprocessing module
  - model_evaluation.py            # Model evaluation module
- results/
  - algorithm_comparison_results.csv  # Results of algorithm comparison
- README.md                      # This README file
- requirements.txt               # Required packages and versions
```

## Getting Started

1. Clone this repository to your local machine.

```bash
git clone https://github.com/your-username/binary-classification-algorithms.git
```

2. Install the required packages by running:

```bash
pip install -r requirements.txt
```

3. Explore the data using the `data_exploration.ipynb` notebook to get familiar with the dataset.

4. Run the `algorithm_comparison.ipynb` notebook to compare the performance of different algorithms.

## Results

The results of the algorithm comparison are saved in the `results/algorithm_comparison_results.csv` file. This file contains the evaluation metrics for each algorithm.

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---
*Disclaimer: This project is for educational and research purposes only and does not provide medical advice. Always consult with a medical professional for breast cancer diagnosis and treatment.*
