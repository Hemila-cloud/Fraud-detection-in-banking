# Fraud-detection-in-banking
from google.colab import files
uploaded = files.upload()
import pandas as pd
df= pd.read_csv('bank_transactions_data_2.csv')
df.head()
df.describe(include='all')
df.info()
df.isna().sum()
df.duplicated().sum()
df.nunique()
