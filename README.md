# Income Classification
This project is classification on the person income with the purpose of predicting whether the person is making above 50$ or below 50$
link to the dataset : https://www.kaggle.com/lodetomasi1995/income-classification

# Code and Libraries Used
Python Version : 3.8.8

Package : Numpy, pandas, matplotlib, Seaborn, Scikit-learn

# Columns
* age: continuous.
* workclass: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.
* fnlwgt: continuous.
* education: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.
* education-num: continuous.
* marital-status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.
* occupation: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport moving, Priv-house-serv, Protective-serv, Armed-Forces.
* relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.
* race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.
* sex: Female, Male.
* capital-gain: continuous.
* capital-loss: continuous.
* hours-per-week: continuous.
* native-country: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.

# Data Cleaning
Replaced ? with Nan

Dropped fnwlgt, education-num,	capital-gain,	capital-loss

Removed null rows with

# Feature Engineering
* Make 2 groups in marital-status column single ,and married 
* Make 4 group in education column vocational, undergraduate, postgraduate, school graduate
* Make 3 group in occupation-level column high level, mid level, low level
* Make 5 group in age column Young, Young Adult, Adult, Elder, Unspecified 
* Replace (-) with ( ) in columns Relationship, Native Country, Workclass, Occupation 





 
