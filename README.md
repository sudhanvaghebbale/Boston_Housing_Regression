# Boston_Housing_Regression
* To use this dataset, use the following command:
  ```
  (train_data,train_targets),(test_data,test_targets) = boston_housing.load_data()
  ```
* To run the notebook, you will need to install the following packages:
  ```
  pip install numpy
  pip install tensorflow
  pip install keras
  pip install matplotlib
  ```

## Dataset Desciption
  * The dataset describes 13 numerical properties of houses in Boston suburbs and is concerned with modeling the price of houses in those suburbs in **thousands of dollars**. The dataset has the following input categories:
    * 'crim': per capita crime rate by town.
    * 'zn': proportion of residential land zoned for lots over 25,000 sq.ft.
    * 'indus': proportion of non-retail business acres per town.
    * 'chas':Charles River dummy variable (= 1 if tract bounds river; 0 otherwise).
    * 'nox': nitrogen oxides concentration (parts per 10 million).
    * 'rm': average number of rooms per dwelling.
    * 'age': proportion of owner-occupied units built prior to 1940.
    * 'dis': weighted mean of distances to five Boston employment centres.
    * 'rad': index of accessibility to radial highways.
    * 'tax': full-value property-tax rate per $10,000.
    * 'ptratio': pupil-teacher ratio by town
    * 'black': 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town.
    * 'lstat': lower status of the population (percent).
    * 'medv': median value of owner-occupied homes in $$1000s
  * Input and output attributes are numerical and there are 506 instances to work with.
  * Performance for models is evaluated using Mean Squared Error (MSE) are around 20 in squared thousands of dollars.
