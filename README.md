# Bengaluru Housing Price Prediction

This project demonstrates a machine learning pipeline for predicting house prices in Bengaluru using a dataset provided in `Bangalore  house data.csv`.

## Structure

- **Bangalore  house data.csv**: Raw dataset containing property details and prices.
- **house-prediction.ipynb**: Jupyter notebook with step-by-step data cleaning, exploratory data analysis, feature engineering, model training, and evaluation.

## Features

- Data preprocessing including missing value handling and feature extraction.
- Outlier detection and removal.
- One-hot encoding of categorical location data.
- Multiple regression models tested (Linear Regression, Lasso, Decision Tree) with grid search for hyperparameters.
- Predictive function for estimating price given inputs.

## Usage

1. Open the Jupyter notebook (`house-prediction.ipynb`) in Jupyter or VS Code.
2. Install necessary Python packages: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`.
3. Run the notebook cells sequentially to reproduce the analysis and model training.

## Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Notes

- The notebook includes extensive commentary and plots illustrating the data and modeling process.
- The final model can be used with the `predict_price` function defined at the end of the notebook.

## License

This repository is provided for educational purposes.