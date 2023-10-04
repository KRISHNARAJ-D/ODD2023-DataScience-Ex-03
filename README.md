# ODD2023-DataScience
# Ex-03 Univariate Analysis
# Aim:
To read the given data and perform the univariate analysis with different types of plots.

# Explanation:
Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data.

# Algorithm:
### Step1:
Read the given data.

### Step2:
Get the information about the data.

### Step3:
Remove the null values from the data.

### Step4:
Mention the datatypes from the data.

### Step5:
Count the values from the data.

### Step6:
Do plots like boxplots,countplot,distribution plot,histogram plot.

# Program:
DEVELOPED BY : KRISHNARAJ D

REGISTER NO : 212222230070
```
import pandas as pd
import numpy as np
import seaborn as sns

df=pd.read_csv('superstore.csv')
df

df.head()
df.info()
df.describe()
df.isnull().sum()

df.dtypes

df['Postal Code'].value_counts()

sns.boxplot(x='Postal Code', data=df)
sns.countplot(x='Postal Code',data=df)
sns.distplot(df["Postal Code"])
sns.histplot(x='Postal Code',data=df)
```
# OUTPUT:
# Dataset:
![272515924-dab07356-02d3-482c-925d-f71090f0c8e5](https://github.com/KRISHNARAJ-D/ODD2023-DataScience-Ex-03/assets/119559695/c3ed9ded-d972-4f6d-9fe0-02be9cb93e54)


# Head:
![272516004-c4bb4ae5-4e51-4b9a-a5f0-b3014cb648ec](https://github.com/KRISHNARAJ-D/ODD2023-DataScience-Ex-03/assets/119559695/c8174ab9-1aee-48b7-bfc0-23a5263850bb)


# Info:
![272516081-6199aaf4-0268-4535-b4c4-3a6ef42b9141](https://github.com/KRISHNARAJ-D/ODD2023-DataScience-Ex-03/assets/119559695/809e69ee-da1b-46bc-8b2a-c37c90dffdb5)

# Describe:

![272516138-ae5c0f59-20eb-4944-af48-1dd2e95b9072](https://github.com/KRISHNARAJ-D/ODD2023-DataScience-Ex-03/assets/119559695/cb27fb7c-65d7-43c1-9470-f485d0e6bf2b)

# Isnull:
![272516201-a5a98935-3097-4af6-8003-ac9d510c8fc2](https://github.com/KRISHNARAJ-D/ODD2023-DataScience-Ex-03/assets/119559695/79fad7a6-5f6d-4aa0-b844-5a1f51cb5dc5)

# dtypes:

![272516284-49c3e822-cc10-4006-9bf1-67b01ac6456f](https://github.com/KRISHNARAJ-D/ODD2023-DataScience-Ex-03/assets/119559695/49366ff6-ee13-48e7-ae6f-fc31b06da4bd)

# Valuecount:
![272516402-04e3240c-4cad-4560-81f5-da78765ee284](https://github.com/KRISHNARAJ-D/ODD2023-DataScience-Ex-03/assets/119559695/0c3e63b3-e8ef-415d-8fc1-399a4bff8856)

# Boxplot:
![272516480-44f74bb3-d204-4f6a-8cb8-66405adad5a1](https://github.com/KRISHNARAJ-D/ODD2023-DataScience-Ex-03/assets/119559695/4ca2b799-f1ec-4920-8afe-f3bbf9f5d94c)

# Countplot:
![272516557-fd880d66-572b-4ee2-9076-f87314fb9b16](https://github.com/KRISHNARAJ-D/ODD2023-DataScience-Ex-03/assets/119559695/03bf88f7-3b29-4c75-bdea-ea5aa046aef4)


# Distribution plot:

![272516754-2b383bc1-a9cd-4daf-90ba-94123fbe416b](https://github.com/KRISHNARAJ-D/ODD2023-DataScience-Ex-03/assets/119559695/d4f0c7dc-ff1e-438b-aad3-7e7327e2e3fd)

# Histogram plot:
![272516818-07e83a45-f8f1-4378-a4a0-f2c37a44d935](https://github.com/KRISHNARAJ-D/ODD2023-DataScience-Ex-03/assets/119559695/c515d754-f075-42d7-b5b0-d603a861e54c)

# Result:
Thus we have read the given data and performed the univariate analysis with different types of plots.
