# mod14c
### Package Requirments & Versions
    *import pandas as pd
    *import numpy as np
    *from pathlib import Path
    *import hvplot.pandas
    *import matplotlib.pyplot as plt
    *from sklearn import svm
    *from sklearn.preprocessing import StandardScaler
    *from pandas.tseries.offsets import DateOffset
    *from sklearn.metrics import classification_report


### Purpose of Use
* Improve existing algorithmic trading systems and maintain firm's competitive advantage in market by enhancing existing trading signals with adaptive machine learning algorithms.

* The code is multiple parts:
    1. Establish baseline performance
    2. Convert baseline trading algorithm
    3. Evaluate new machine learning classifier 
    4. Create evaluation report 
    
    
### Files Navigation
* `machine_learning_trading_bot.ipynb`: Code explanation and building
* `applicants_data.csv`



##Establishing Baseline Performance: 

This model establishes a baseline performance of around 56% with a return estimating 50%. The following parameters were set as follows; SMA short window=4D, SMA long window= 100D, training data set to 3 months from start of data. 





### Step 1: Tune the training algorithm by adjusting the size of the training dataset. 

To do so, slice your data into different periods. Rerun the notebook with the updated parameters, and record the results in your `README.md` file. 

Answer the following question: What impact resulted from increasing or decreasing the training window?

Increasing the dataset to 6 months improved the accuracy and return compared to the baseline. 


 

### Step 2: Tune the trading algorithm by adjusting the SMA input features. 

Adjust one or both of the windows for the algorithm. Rerun the notebook with the updated parameters, and record the results in your `README.md` file. 

Answer the following question: What impact resulted from increasing or decreasing either or both of the SMA windows?

When the SMA windows were decreased, the accuracy increased, while the return decreased compared to baseline.





### Step 3: Backtest the new model to evaluate its performance. 

Save a PNG image of the cumulative product of the actual returns vs. the strategy returns for this updated trading algorithm, and write your conclusions in your `README.md` file. 

Answer the following questions: 
Did this new model perform better or worse than the provided baseline model? Did this new model perform better or worse than your tuned trading algorithm?


Both have similar accuracies, however the new model has an increased rate of return, indicating the new model performs better. 

