# Predict-CO2-Emissions

## Question
Given the dataset, can we predict the Co2 emission of a car using another field such as engine size?

### The data 
Fuel consumption dataset, FuelConsumption.csv, contains model-specific fuel consumption ratings and estimated carbon dioxide emissions for new light-duty vehicles for retail sale in Canada. [Dataset source](https://open.canada.ca/data/en/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkML0101ENSkillsNetwork1047-2023-01-01) 

* MODELYEAR e.g. 2014
* MAKE e.g. Acura
* MODEL e.g. ILX
* VEHICLE CLASS e.g. SUV
* ENGINE SIZE e.g. 4.7
* CYLINDERS e.g 6
* TRANSMISSION e.g. A6
* FUELTYPE e.g. z
* FUEL CONSUMPTION in CITY(L/100 km) e.g. 9.9
* FUEL CONSUMPTION in HWY (L/100 km) e.g. 8.9
* FUEL CONSUMPTION COMB (L/100 km) e.g. 9.2
* CO2 EMISSIONS (g/km) e.g. 182 --> low --> 0

### Explore the linear relationship between independent variables and dependent variable (C02 emissions)
<p align="left">
  <img src="https://imgur.com/7BgFxYs.png" alt="Fuel Consumption vs Co2 Emmissions" />
</p>
<p align="center">
  <img src="https://imgur.com/2yEplDY.png" alt="Number of cylinders vs Co2 Emmissions" />
</p>
<p align="right">
  <img src="https://imgur.com/ElcKLuT.png" alt="Engine size vs Co2 Emmissions" />
</p>

## Results

### Simple Linear Regression

__Accuracy__ :
Mean absolute error: 23.67

Residual sum of squares (MSE): 937.54

R2-score: 0.76

### Multiple Linear Regression

__Accuracy__ :

Coefficients: [[12.15449154  7.11953684  5.38396602  3.69373359]]

Residual sum of squares: 554.93

Variance score: 0.86
 