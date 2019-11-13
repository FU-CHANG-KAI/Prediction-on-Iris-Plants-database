# Prediction on Iris Plants database
In this repository, a linear regression model is built with numpy, matplotlib and pandas to classify four features of Iris Plants. The attribute information is as below:
1. sepal length in cm
2. sepal width in cm
3. petal length in cm
4. petal width in cm
5. class:
-- Iris Setosa
-- Iris Versicolour
-- Iris Virginica

Two of classes are chosen to be classified: Iris_setosa and Iris_versicolor

## Installation
```bash
Numpy
Matplotlib
Pandas
```

## Usage
```bash
%matplotlib inline
import numpy as np
import matplotlib.pyplot as plt
import pandas as pd
```

## Steps to build the model
1. Load the database
```bash
df = pd.read_csv('iris.data', header=None)
```
2. extract data of four features
3. Divide the database to train and test data with 1 or -1 label
4. Calculate the accuracy percentage before the nodel is trained 
5. Train the model with function PercentCorrect
5. Calculate the accuracy percentage after the nodel is trained 

## Limitation
This is still under construction. More features will be presented in the near feature.

## Example Outcome
1.Accuracy

train: 100%

test: 96%

2. Learning curve
<img src="image/Scatter%20plot%20of%20Iris%20Plants.PNG" width="100">

<img src="image/Learning%20curve.PNG" width="100">

## Source of data
http://archive.ics.uci.edu/ml/datasets/Iris

## Contriduting
Note that the kit is still under construction. Pull requests are welcome. For major changes, please contact me via the mail fuchangkai153@gmail.com
