# A chocolate manufacturer cost evaluation and demand forecast capstone 

The raw data is manipulated data minics a chocolate manufacturer, provded by Kikodo https://www.kikodo.io/. 

Section 1 includes: 
- find out the cheapest supplier for each ingredient 
- calculate the total cost of each supplier based on demand 
- calculate the total tax of each supplier based on demand 
- identify the cheapest supplier per recipe 
- identify the total cost (inc. tax) to meet all demand per quarter with the fastest suppliers

Section 2: Machine Learning -train and test forecast models (Linear Regression, DTR, KNN and Gradient Descent Regression). Built a forecast model with a R2 score of r2 score of 0.883 to predict the demand more accurately. 

The key steps include: 
- exploratory data analysis
- data preprocessing
- create features with assumptions
- explore the features' correlation with the model(s)
- model selection and performance metrics comparison 
- cross-validation 
- create and select polynomial features to test the new parameter's importance in the selected model 
- train the selected model with permutation features   
- evaluate the model by visualizing the forecasted demand with comparision to the test data
- finalize the model features and evaluation
