# Ex03-Univariate-Analysis
# Aim
To read the given data and perform the univariate analysis with different types of plots.

# Explanation
Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data.

# Algorithm
Step1
Read the given data.

Step2
Get the information about the data.

Step3
Remove the null values from the data.

Step4
Mention the datatypes from the data.

Step5
Count the values from the data.

Step6
Do plots like boxplots,countplot,distribution plot,histogram plot.
# program 
Developed by : SWATHI D
Registration Number : 212222230154

import pandas as pd
import numpy as np
import seaborn as sns
df=pd.read_csv("SuperStore.csv")
df
df.head()
df.info()
df.describe()
df.isnull().sum()
df.dtypes
df['Postal Code'].value_counts()
sns.boxplot(x="Postal Code", data=df)
sns.countplot(x="Postal Code", data=df)
sns.distplot(df["Postal Code"])
sns.histplot(x="Postal Code", data=df)

# OUTPUT


# DATA
![Screenshot 2023-03-29 142343](https://user-images.githubusercontent.com/120440439/228483553-3cb35e71-5166-47ed-b0c4-0b6b06f21340.png)

# DATA HEAD
![Screenshot 2023-03-29 142406](https://user-images.githubusercontent.com/120440439/228483690-07800721-8a7d-4a01-a832-0948e1745c65.png)

# DATA INFORMATION
![Screenshot 2023-03-29 142418](https://user-images.githubusercontent.com/120440439/228483815-6f07985a-504e-41e1-8c4b-feaa34d23969.png)

# DATA DESCRIBE
![Screenshot 2023-03-29 142425](https://user-images.githubusercontent.com/120440439/228483914-290012db-bd0b-4b6c-848f-7340b0d9878b.png)

# DATA NULL VALUES
![Screenshot 2023-03-29 143823](https://user-images.githubusercontent.com/120440439/228485220-87ff56a8-0097-4175-848c-dd2914c52c3a.png)

# DATA DATA TYPES
![Screenshot 2023-03-29 142438](https://user-images.githubusercontent.com/120440439/228485396-dc3a331d-35ba-46a3-a1cf-db23dd29e96d.png)

# DATA VALUE COUNT
![Screenshot 2023-03-29 142509](https://user-images.githubusercontent.com/120440439/228485442-2de67d08-a686-4dd2-bd34-7bea7510d61b.png)

# BOXPLOT
![Screenshot 2023-03-29 142517](https://user-images.githubusercontent.com/120440439/228485477-7df8f95a-0e2b-4c89-a96b-2109745a4774.png)

# COUNTPLOT
![Screenshot 2023-03-29 142524](https://user-images.githubusercontent.com/120440439/228485516-a9a765db-8841-45af-bff6-aff0e6e005f3.png)

# DISTRIBUTION PLOT
![Screenshot 2023-03-29 142531](https://user-images.githubusercontent.com/120440439/228485589-57b17f29-2115-4c1a-bd89-3977f2485114.png)

# HISTOGRAM PLOT
![Screenshot 2023-03-29 142538](https://user-images.githubusercontent.com/120440439/228485637-7872f8e5-4ce3-481c-be62-1e730e012888.png)

# RESULT
Thus we have read the given data and performed the univariate analysis with different types of plots.
