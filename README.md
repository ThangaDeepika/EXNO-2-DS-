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
```
![](2-1.png)
![Screenshot 2024-03-13 170503](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/0be336dd-1b09-44ee-baf7-a66f02d1bee6)
![Screenshot 2024-03-13 170514](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/0581773b-82c4-4269-b6ff-065b072d2fd1)
![Screenshot 2024-03-13 170521](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/1d0afaf1-14ad-4dd3-97ca-a6081a21b841)
![Screenshot 2024-03-13 170528](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/25986eb4-415a-4a4d-b620-b9ffde0d9f3a)
![Screenshot 2024-03-13 170540](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/f380b495-ad5c-4602-ac34-bd912bb249f8)
![Screenshot 2024-03-13 170540](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/f380b495-ad5c-4602-ac34-bd912bb249f8)
![Screenshot 2024-03-13 170602](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/303b7836-4abb-4967-a4a8-cec72ddd2fb6)
![Screenshot 2024-03-13 170602](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/9925f321-88dd-4c57-b194-bf9b9031251c)
![Screenshot 2024-03-13 170639](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/bd66d412-cd20-4de7-a63a-5111f0f06bb9)
![Screenshot 2024-03-13 170639](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/bd66d412-cd20-4de7-a63a-5111f0f06bb9)
![Screenshot 2024-03-13 170655](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/f1cf0adc-da15-49de-8417-7551ea2567c0)
![Screenshot 2024-03-13 170703](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/c1d63572-578c-4cd2-9b4c-c7f1266d990e)
![Screenshot 2024-03-13 170655](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/5e3b16c3-3142-4ddc-bba9-e3610429ff9c)
![Screenshot 2024-03-13 170733](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/bfb40d89-de55-4d8d-aad5-191538e065eb)
![Screenshot 2024-03-13 170842](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/127fb422-596c-4021-9471-475f4ead16dc)
```
sns.pairplot(dt)
```
![2-17](https://github.com/ThangaDeepika/EXNO-2-DS-/assets/125663099/e4d5f598-f11d-450c-9bd1-2556415ad53c)

# RESULT
        Exploratory Data Analysis on the given data set was created and executed successfully.
