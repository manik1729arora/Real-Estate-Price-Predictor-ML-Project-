# ML Project: Predicting Real Estate Prices

- Model for predicting house prices for a given a set of features.

- Concepts used :- Cross validation, Train-test splitting, Stratified shuffle split and Sampling work.

 [https://archive.ics.uci.edu/ml/machine-learning-databases/housing/]


### Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://jupyter.org/install.html).

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](https://www.anaconda.com/download/) distribution of Python, which already has the above packages and more included. 


### Data

The Boston housing dataset consists of 506 data points, with each datapoint having 13 features. This dataset is a modified version of the Boston Housing dataset found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/machine-learning-databases/housing/)
.

**Features**
1. `CRIM`     per capita crime rate by town

2. `ZN`       proportion of residential land zoned for lots over 
                 25,000 sq.ft.

3. `INDUS`     proportion of non-retail business acres per town

4. `CHAS`      Charles River dummy variable (= 1 if tract bounds 
                 river; 0 otherwise)

5. `NOX`       nitric oxides concentration (parts per 10 million)

6. `RM`        average number of rooms per dwelling

7. `AGE`       proportion of owner-occupied units built prior to 1940

8. `DIS`       weighted distances to five Boston employment centres

9. `RAD`      index of accessibility to radial highways

10. `TAX`      full-value property-tax rate per $10,000

11. `PTRATIO`  pupil-teacher ratio by town

12. `Bk`        1000(Bk - 0.63)^2 where Bk is the proportion of blacks 
                 by town

13. `LSTAT`    % lower status of the population

**Target Variable**
14. `MEDV`: median value of owner-occupied homes
