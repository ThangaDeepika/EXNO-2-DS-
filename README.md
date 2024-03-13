# EXNO2DS
# AIM:
      To perform Exploratory Data Analysis on the given data set.
      
# EXPLANATION:
  The primary aim with exploratory analysis is to examine the data for distribution, outliers and anomalies to direct specific testing of your hypothesis.
  
# ALGORITHM:
STEP 1: Import the required packages to perform Data Cleansing,Removing Outliers and Exploratory Data Analysis.

STEP 2: Replace the null value using any one of the method from mode,median and mean based on the dataset available.

STEP 3: Use boxplot method to analyze the outliers of the given dataset.

STEP 4: Remove the outliers using Inter Quantile Range method.

STEP 5: Use Countplot method to analyze in a graphical method for categorical data.

STEP 6: Use displot method to represent the univariate distribution of data.

STEP 7: Use cross tabulation method to quantitatively analyze the relationship between multiple variables.

STEP 8: Use heatmap method of representation to show relationships between two variables, one plotted on each axis.

## CODING AND OUTPUT
```
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
dt=pd.read_csv("/content/titanic_dataset.csv")
dt
![Screenshot 2024-03-13 170454](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/dd4777ed-b32a-4a2b-8246-7f51d6f71cbd)
![Screenshot 2024-03-13 170503](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/373dde3c-f20b-4555-ac25-688ca830d245)
![Screenshot 2024-03-13 170514](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/9131e145-33db-4f3f-8ef1-19311d37cf16)
![Screenshot 2024-03-13 170521](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/92c279ab-a26d-40a7-a17f-ab0b80e0b9b0)
![Screenshot 2024-03-13 170528](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/ae2857a3-1e70-4b63-b29a-bb682dfb6428)
![Screenshot 2024-03-13 170540](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/0d777afa-5153-4104-9c12-f4695f733497)
![Screenshot 2024-03-13 170551](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/50da571a-b410-4b19-bca4-5ab534bacf24)
![Screenshot 2024-03-13 170602](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/c99f24d4-89b6-45f9-b350-7720a74ded6e)
![Screenshot 2024-03-13 170609](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/3e50388a-530d-40f2-9b65-e736cbe32020)
![Screenshot 2024-03-13 170639](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/199bb918-7613-4550-b5ee-72bbf83b7c82)
![Screenshot 2024-03-13 170648](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/02db7c01-1694-4d89-bf77-73cd575f6218)
![Screenshot 2024-03-13 170655](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/f448de2f-da20-4d7c-9c3c-bcd167498c4e)
![Screenshot 2024-03-13 170703](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/3fd90b04-2f22-47c3-9c8e-fd56cbeb3bcb)
![Screenshot 2024-03-13 170722](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/7e17e137-a3f8-4b9d-bf7f-a23df9fc8428)
![Screenshot 2024-03-13 170733](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/3bbb06d8-25b4-4cea-85d0-869dc3fc883c)
![Screenshot 2024-03-13 170842](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/444ac9d7-1933-46f5-8600-d949d2f980a0)
sns.pairplot(dt)
![image](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/bd42cf03-5360-49bb-972d-42e9e21312c1)
```


# RESULT
        Exploratory Data Analysis on the given data set was created and executed successfully.
