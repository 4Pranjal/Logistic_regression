# Logistic Regression with Grid Search and Exploratory Data Analysis (EDA)

Welcome to the Logistic Regression with Grid Search and EDA project! In this repository, we explore a Python script that showcases the process of building a Logistic Regression classifier, optimizing its hyperparameters using grid search, and conducting Exploratory Data Analysis (EDA) on the well-known Iris dataset.

## Introduction

This project serves as an educational demonstration of various key concepts in machine learning and data analysis:

1. **Logistic Regression:** We use the Logistic Regression algorithm to create a classifier that can distinguish between different species of the Iris flower based on their features.

2. **Grid Search:** To enhance the performance of our classifier, we employ grid search, an approach that systematically searches through a predefined set of hyperparameters to identify the best combination for optimal model performance.

3. **Exploratory Data Analysis (EDA):** Before building the classifier, we visualize the dataset's features using pair plots and correlation matrices, providing insights into potential relationships and correlations among the variables.

## Code Explanation

The code within this repository follows a structured approach:

1. **Data Loading and Preprocessing:** We load the Iris dataset using the Seaborn library, eliminate the 'setosa' species, and encode the 'versicolor' and 'virginica' species as numerical values (0 and 1).

2. **Data Splitting:** The dataset is divided into training and testing sets using the `train_test_split` function from `sklearn`.

3. **Logistic Regression with Grid Search:** We initiate a Logistic Regression classifier, define a parameter grid for hyperparameter tuning, and employ grid search with cross-validation via `GridSearchCV` from `sklearn`. The best parameters and corresponding score are printed.

4. **Prediction and Evaluation:** Our trained classifier is employed to predict the test set's outcomes. We evaluate the classifier's performance using accuracy scores and a classification report.

5. **Exploratory Data Analysis (EDA):** We construct a pair plot to visually analyze feature relationships, color-coded by species. Additionally, we calculate the correlation matrix, which aids in understanding potential feature correlations.

## How to Use

Follow these steps to run the provided Python script:

1. Clone the repository to your local machine:

```bash
git clone https://github.com/4Pranjal/Logistic-Regression-Grid-Search-EDA.git
```

2. Navigate to the repository's directory:

```bash
cd Logistic-Regression-Grid-Search-EDA
```

3. Run the Python script:

```bash
python logistic_regression_grid_search.ipynb
```

## Requirements

Ensure you have the following dependencies installed:

- Python 3.x
- Seaborn
- Pandas
- Numpy
- Scikit-learn

## License

This project is licensed under the [MIT License](LICENSE).

## Credits

This repository is maintained by 4Pranjal. Feel free to use and modify the code for educational and research purposes.

For any questions or suggestions, you can contact me through my GitHub profile: [@4Pranjal](https://github.com/4Pranjal).

Made with ❤️ by [Pranjal Jain](https://github.com/4Pranjal)
