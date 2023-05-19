# Ex-10-Data-Science-Process-on-Complex-Dataset

## AIM
To Perform Data Science Process on a complex dataset and save the data to a file. 

# ALGORITHM
### STEP 1
Read the given Data.
### STEP 2
Clean the Data Set using Data Cleaning Process.
### STEP 3
Apply Feature Generation/Feature Selection Techniques on the data set.
### STEP 4
Apply EDA /Data visualization techniques to all the features of the data set

# DATA PREPROCESSING
```
import pandas as pd
import numpy as np
import seaborn as sns
from google.colab import files
uploaded = files.upload()
df = pd.read_csv("annual_balance.csv")
df
df.head()
```
![image](https://github.com/ManiKandan228/Ex-10-Data-Science-Process-on-Complex-Dataset/assets/119160414/45c8afb7-2a2b-47a4-be89-c201ba2a12f8)

![image](https://github.com/ManiKandan228/Ex-10-Data-Science-Process-on-Complex-Dataset/assets/119160414/cfc5b441-1b5d-482d-971d-df25ceca7943)

# DATA CLEANING
![image](https://github.com/ManiKandan228/Ex-10-Data-Science-Process-on-Complex-Dataset/assets/119160414/0624c40a-7503-41fa-a590-adbca9246384)
