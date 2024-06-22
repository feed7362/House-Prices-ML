# House Prices - Advanced Regression Techniques Kaggle Competition

# Overview

This project is based on the House price Kaggle competition, where the goal is to predict price based on house characteristics.

# Files

List and briefly describe the main files in your repository:

- House price (ML).ipynb: Jupyter notebook containing the main analysis, modeling code and some statistic.

- train.csv: CSV file containing the training dataset.

- test.csv: CSV file containing the test dataset for making predictions.

- submission.csv: CSV file containing the predictions for the test set.

- data_description.txt: txt file describes 81 data column

# Dependencies

- Python 3

- pandas

- numpy

- scikit-learn

# Usage

Clone this repository:

```sh
git clone https://github.com/feed7362/House-Prices-ML.git
```
Navigate to the project directory:

```sh
cd House-Price-ML
```
Install dependencies:
```sh
pip install -r requirements.txt
```
Open and run the House price (ML).ipynb notebook using Jupyter or any compatible environment.

# Approach

- Data preprocessing: Handling missing values, feature engineering.

- Model selection: Random Forest Regression, Hist Gradient Boosting Regressor.

- Model evaluation: Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price.

# Results

## Accuracy achieved on the test set.

### Random Forest Regressor

- Kaggle accuracy:  0.17894

- Random accuracy from dataset: 0.13278

### Hist Gradient Boosting Regressor

- Kaggle accuracy:  0.15139

- Random accuracy from dataset: 0.13552

# Kaggle Competition

- For more details on the Kaggle House Prices - Advanced Regression Techniques competition, visit [**Kaggle House Prices - Advanced Regression Techniques Competition.**](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/)

- Author: Kaggle

## LICENSE
<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />All material is available under [Creative Commons BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/). You can **use, redistribute, and adapt** the material for **non-commercial purposes**, as long as you give appropriate credit by **citing our paper** and **indicate any changes** you've made.
