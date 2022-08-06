# Predicting fuel consumption of various vehicles rode in cities:
This project evaluates methods of Machine Learning (ML) and statistical analysis for
predicting fuel consumption of various vehicles rode in cities.
The general problem description is to examine a large number of attributes describing a fuel consumption situation and to employ ML methods to find a regression
from such attributes to a fuel consumption. Attributes included are MPG (Miles per Gallon),Cylinders,Displacement,Horsepower,Weight,Acceleration,Model year,Origin,Car Name

## Insight about the given dataset:
- Dataset: competition_edu_dataset.csv
- Total No. Of Attributes: 9
- Total No. Of Instances:300
- Attributes:
```bash
 1.MPG - Mileage/Miles Per Gallon
 2.Cylinders - The power unit of the car where gasoline is turned into power
 3.Displacement - Engine displacement of the car
 4.Horsepower - Rate of the engine performance
 5.Weight - The weight of a car
 6.Acceleration - The acceleration of a car
 7.Model Year - Model of the car
 8.Origin - The origin of the car
 9.Car Name - The name of the car
```
## Libraries Used:
- Numpy
- Pandas
- Statsmodels
- Sklearn
#### For Encoding Categorical Data:
- from sklearn.compose import ColumnTransformer
- from sklearn.preprocessing import OneHotEncoder
#### For Splitting Dataset:
- from sklearn.model_selection import train_test_split
#### For Linear Regression:
- from sklearn.linear_model import LinearRegression
#### For Random Forest Regressor:
- from sklearn.ensemble import RandomForestRegressor
#### For Score:
- from sklearn.metrics import r2_score,mean_squared_error

## References:
> https://docs.python.org/3/
> https://numpy.org/doc/
> https://pandas.pydata.org/docs/
> https://www.statsmodels.org/stable/index.html
> https://scikit-learn.org/stable/modules/generated/sklearn.compose.ColumnTransformer.html
> https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.OneHotEncoder.html
> https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html
> https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html
> https://scikitlearn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html
> https://scikit-learn.org/stable/modules/generated/sklearn.metrics.r2_score.html


