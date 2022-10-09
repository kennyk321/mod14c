# mod14c
### Package Requirments & Versions
import pandas as pd
import numpy as np
from pathlib import Path
import hvplot.pandas
import matplotlib.pyplot as plt
from sklearn import svm
from sklearn.preprocessing import StandardScaler
from pandas.tseries.offsets import DateOffset
from sklearn.metrics import classification_report


### Purpose of Use
* Create model that predicts applicants success if funded by Alphabet Soup by creating binary classifier model. 

* The code is multiple parts:
    1. here
    2. 
   
    
    
### Files Navigation
* `machine_learning_trading_bot.ipynb`: Code explanation and building
* `applicants_data.csv`


### Step 3: Backtest the new model to evaluate its performance. 

Save a PNG image of the cumulative product of the actual returns vs. the strategy returns for this updated trading algorithm, and write your conclusions in your `README.md` file. 

Answer the following questions: 
Did this new model perform better or worse than the provided baseline model? Did this new model perform better or worse than your tuned trading algorithm?


Both have similar accuracies, however the new model has an increased rate of return, indicating the new model performs better. 

<img width="814" alt="Strategy vs Actual Returns Screenshot" src="https://user-images.githubusercontent.com/95942698/194760568-b21545b8-d421-491e-ab0a-87f1b654fedd.png">

