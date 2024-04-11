# Decision Trees Project

This project demonstrates the implementation of Decision Trees for classification using Python, particularly focusing on the `sklearn` library. It utilizes the Heart Disease dataset from the UCI Machine Learning Repository.

## Dataset

The dataset used in this project is the Cleveland Heart Disease dataset obtained from the UCI Machine Learning Repository. It contains various attributes such as age, sex, cholesterol levels, and more, with a target variable indicating the presence or absence of heart disease.

## Preprocessing

- Data was retrieved from the UCI repository and stored locally.
- Missing values denoted by "?" were imputed using the mode of respective columns.
- Categorical features were encoded using LabelEncoder.
- Outliers were detected and removed using the IQR method.
- Standard scaling was applied to normalize the numerical features.

## Modeling

- Decision Tree Classifier was trained on the preprocessed data.
- A default Decision Tree model was also trained for comparison.
- The performance of both models was evaluated using classification metrics.

## Files

- `decision_trees.ipynb`: Jupyter Notebook containing the Python code for data preprocessing, modeling, and evaluation.
- `heart.csv`: The dataset used in the project.
- `README.md`: This file providing an overview of the project.

## Dependencies

- Python 3
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Usage

1. Clone the repository.
2. Open `decision_trees.ipynb` in Jupyter Notebook or Google Colab.
3. Run the cells sequentially to execute the code.
4. Explore the results and analysis provided in the notebook.

## Acknowledgments

- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)

