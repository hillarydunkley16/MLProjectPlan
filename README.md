Lab 8a from Break Through Tech AI 
Logistic Regression model on census data 

We will be predicting whether a given person has a yearly salary of more than or less than 50k. The label is income_binary.
This is a supervised learning problem, and a logistic regression problem.
Features are age, workclass, education-num, marital-status, occupation, race, sex_selfID, hours-per-week, native-country
This is important to know what types of people are making less than or more than 50k (a somewhat livable wage). This could be important for politics, so a polititian knows what percentage of their constituency is poor so that they can tailor policies that will benefit potential voters.

I did a lot of data preparation -> filling in missing values, imputing, fixing spelling mistakes and consolidating similar data points 

The model is fairly accurate, with an accuracy rate of .82 

To run this program you need to import: 
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - sklearn

Below are all of the import statements from our program: 

import pandas as pd
import numpy as np
import os 
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.linear_model import LogisticRegression
from sklearn.model_selection import train_test_split 
from sklearn.metrics import log_loss
from sklearn.metrics import accuracy_score
