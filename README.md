# Customer Conversion Prediction
 This is a repository of my personal project about customer conversion prediction with supervised machine learning. 
 The data used in this project is audio books app customer conversion data. The goal of this project is to create classification model 
 that can predicts whether the customer will buy again (convert) or not.
 
 ## Usage
 The project is implemented in Python and uses the [PyCaret](https://pycaret.gitbook.io/docs/) library for machine learning model training and evaluation.

There are 2 notebooks in this repo. Ideal order for reading: `customer_conversion_baseline.ipynb` -> `customer_conversion_model.ipynb`

Notebook | Description | Colab
------------- | ------------- | -------------
`customer_conversion_baseline.ipynb` | Starting notebook of this project, contains EDA and feature engineering, also baseline modelling using Pycaret library | [![open-in-colab]](https://colab.research.google.com/drive/1kUEGvKLkBLwwUHY0i9dwlHPW76holiLi?usp=sharing)
`customer_conversion_model.ipynb` | Final modelling notebooks, using LightGBM model, deeper into model tuning and evaluation | [![open-in-colab]](https://colab.research.google.com/drive/1Fjcu6EP2dnJ4r2AbYRKGKRVTN7T_K4eA?usp=sharing)

[open-in-colab]: https://colab.research.google.com/assets/colab-badge.svg
