# Credit-card-payment-prediction

This research aimed at the case of customers default payments in Taiwan and compares the predictive accuracy of probability of default among six data mining methods. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients.

## Install:

* Numpy
* Pandas 
* Matplotlib
* Scikit-learn

You will also need to have software installed to run and execute a Jupyter Notebook

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included.

## Code:

Template code is provided in the “credit card payment prediction-raw-code.ipynb” inside the code folder. This is by using the raw code implementation. 

Template code for the sklearn implementation is provided in the “credit card payment prediction-sklearn.ipynb” inside the code folder.

Also include the data set “default of credit card clients.xls” while running the code.

## Run:

In a anaconda promt or in the  terminal, navigate to the code folder and run one of the following commands:

      jupyter notebook "credit card payment prediction-raw-code.ipynb"

      jupyter notebook "credit card payment prediction-sklearn.ipynb"

This will open the Jupyter Notebook software and project file in your browser.

## Dataset information:

This research aimed at the case of customers default payments in Taiwan and compares the predictive accuracy of probability of default among six data mining methods. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients. Because the real probability of default is unknown, this study presented the novel Sorting Smoothing Method to estimate the real probability of default. With the real probability of default as the response variable (Y), and the predictive probability of default as the independent variable (X), the simple linear regression result (Y = A + BX) shows that the forecasting model produced by artificial neural network has the highest coefficient of determination; its regression intercept (A) is close to zero, and regression coefficient (B) to one. Therefore, among the six data mining techniques, artificial neural network is the only one that can accurately estimate the real probability of default.

## Attribute Information:

* X1: Amount of the given credit (NT dollar)
* X2: Gender (1 = male; 2 = female). 
* X3: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others)
* X4: Marital status (1 = married; 2 = single; 3 = others). 
* X5: Age (year).
* X6 - X11: History of past payment. We tracked the past monthly payment records (from April to September, 2005)
* X12-X17: Amount of bill statement (NT dollar). ( From April to September 2005)
* X18-X23: Amount of previous payment (NT dollar). (Amount paid from April to September 2005)

## Output variable (desired target):

      “default payment next month”


## Models trained on:

| Algorithm                         | Accuracy|
| --- | --- | 
| Logistic regression               | 80.48 % |
| Logistic regression using sklearn | 81.12 % |







