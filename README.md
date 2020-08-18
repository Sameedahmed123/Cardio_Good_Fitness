# Background Information

- The market research team at AdRight is assigned the task to identify the profile of the typical customer for each treadmill product offered by CardioGood Fitness. 
- The market research team decides to investigate whether there are differences across the product lines with respect to customer characteristics.
- The team decides to collect data on individuals who purchased a treadmill at a CardioGoodFitness retail store during the prior three months.

## CardioGoodFitness - Project Overview

- Analyzing which customer characteristic have the most impact on the product sale.
- EDA
- Optimized Linear, Decision Tree and Random forrest Regressors to reach the best model.

#### Code and Resources Used

**Python Version** : 3.7

**Packages** : Pandas, Matplotlib, Seaborn, Sklearn, numpy, scipy

**Github** : https://www.kaggle.com/saurav9786/cardiogoodfitness

#### Model Building

I also split the test and train data.

I tried three different models, evaluated them using mean absolute error, I chose MAE because it is relatively easy to interpret.

I tried these models:
- **Linear Regression** - Baseline for the model
- **Decision Tree** - Better classification and regression model than linear ( But here Linear Regression performed better )
- **Random Forest** - None or least modification to get the best fit

#### Model Performance

- **Linear Regression**: MAE = 15.92
- **Decision Tree**: MAE = 20.00
- **Random Forest** : MAE = 19.99
