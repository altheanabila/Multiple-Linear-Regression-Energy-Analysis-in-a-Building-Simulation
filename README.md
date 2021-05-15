# Multiple-Linear-Regression-Energy-Analysis-in-a-Building-Simulation

I try to simulate a multiple linear regression which I have downloaded the data from Kaggle (https://www.kaggle.com/elikplim/eergy-efficiency-dataset?select=ENB2012_data.csv). I try to find out the relationship between these variables:;

- X1 Relative Compactness
- X2 Surface Area
- X3 Wall Area
- X4 Roof Area
- X5 Overall Height
- X6 Orientation
- X7 Glazing Area
- X8 Glazing Area Distribution
- y1 Heating Load

1. Import related libraries


![testimage1](https://github.com/altheanabila/Multiple-Linear-Regression-Energy-Analysis-in-a-Building-Simulation/blob/main/pic%201.png)

2. Extracting into data panda frames

![testimage1](https://github.com/altheanabila/Multiple-Linear-Regression-Energy-Analysis-in-a-Building-Simulation/blob/main/pic%202.png)


3. Define X and Y variables through this line of code

![Testimage1](https://github.com/altheanabila/Multiple-Linear-Regression-Energy-Analysis-in-a-Building-Simulation/blob/main/pic%203.png)


4. Run this code to get the result of OLS. All variables are significant with high Rsquare stood at 91,6%
`lm_multi = sn.OLS(y_multi, X_multi_cons).fit()`
`lm_multi.summary()`

![Testimage1](https://github.com/altheanabila/Multiple-Linear-Regression-Energy-Analysis-in-a-Building-Simulation/blob/main/pic%204.png)


5. Visualize the graph in 3D graph

![Testimage1](https://github.com/altheanabila/Multiple-Linear-Regression-Energy-Analysis-in-a-Building-Simulation/blob/main/pic%205.png)
![Testimage1](https://github.com/altheanabila/Multiple-Linear-Regression-Energy-Analysis-in-a-Building-Simulation/blob/main/pic%206.png)




![Testimage1](https://github.com/altheanabila/Multiple-Linear-Regression-Energy-Analysis-in-a-Building-Simulation/blob/main/pic%207.png)
![Testimage1](https://github.com/altheanabila/Multiple-Linear-Regression-Energy-Analysis-in-a-Building-Simulation/blob/main/pic%208.png)




![Testimage1](https://github.com/altheanabila/Multiple-Linear-Regression-Energy-Analysis-in-a-Building-Simulation/blob/main/pic%209.png)
![Testimage1](https://github.com/altheanabila/Multiple-Linear-Regression-Energy-Analysis-in-a-Building-Simulation/blob/main/pic%2010.png)

