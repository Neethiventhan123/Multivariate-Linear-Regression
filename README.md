# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
import pandas as pd

### Step2
read the csv file

### Step3
get the value of x and y varibles

### Step4
create the linear regresssion model and fit

### Step5
print the predicted output

developed by:N.neethiventhan

reference number:23006643

## Program:
```python
#Developed by:N.Neethiventhan
#Reg no:23006643
import pandas as pd
from sklearn import linear_model
df=pd.read_csv("cars (1).csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("Coefficient:",regr.coef_)
print("Intercept:",regr.intercept_)
print("Amount:",regr.predict([[3300,1300]]))

```
## Output:
![image](https://github.com/Neethiventhan123/Multivariate-Linear-Regression/assets/148514848/1cac2b34-33f0-4031-b6d4-500549f496b5)

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
