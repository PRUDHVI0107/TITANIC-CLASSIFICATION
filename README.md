# TITANIC-CLASSIFICATION
import pandas as pd 
import matplotlib.pyplot as plt
from sklearn.model_selection import train_test_split
from sklearn.metrics import r2_score
from sklearn.metrics import mean_absolute_error
from sklearn.ensemble import RandomForestClassifier
df= pd.read_csv("/content/Titanic-Dataset.csv")
df.shape
![image](https://github.com/PRUDHVI0107/TITANIC-CLASSIFICATION/assets/109857212/6f4847c6-2a94-467c-a1e8-c7d780565533)
