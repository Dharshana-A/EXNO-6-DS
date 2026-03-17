# EXNO-6-DS-DATA VISUALIZATION USING SEABORN LIBRARY

# Aim:
  To Perform Data Visualization using seaborn python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
 ```
import seaborn as sns
import pandas as pd
df=pd.read_csv("iris.csv")
df.head()
sns.jointplot(x="petal_length", y="petal_width", data=df, kind="hex")
sns.pairplot(data=df, vars=["sepal_length","sepal_width"], hue="species")
sns.displot(df["petal_length"], kde=True)
sns.countplot(y="species", data=df)
sns.boxplot(x="species", y="petal_length", data=df)
sns.barplot(x="species", y="petal_length", data=df)
sns.violinplot(x="species", y="petal_length", data=df)
```
<img width="882" height="679" alt="image" src="https://github.com/user-attachments/assets/42dd7331-e74a-42ca-9b50-5d8e3c37542e" />
<img width="907" height="700" alt="image" src="https://github.com/user-attachments/assets/85422cfd-e742-450d-ae28-b8b2836a92ec" />
<img width="905" height="707" alt="image" src="https://github.com/user-attachments/assets/804fc0d2-5ea1-43c5-aa12-1089e292e6c6" />
<img width="989" height="696" alt="image" src="https://github.com/user-attachments/assets/b5831428-638b-4dd3-a632-74b600134b3f" />
<img width="680" height="677" alt="image" src="https://github.com/user-attachments/assets/95994f44-8bba-4e7b-ae1f-952dd2e2aadc" />
<img width="885" height="709" alt="image" src="https://github.com/user-attachments/assets/915081ee-1e3c-4ac9-9f3b-cbe32e6c1299" />
<img width="740" height="751" alt="image" src="https://github.com/user-attachments/assets/e1790825-e667-48f9-bc9b-e6f6cc8bab28" />
<img width="1031" height="263" alt="image" src="https://github.com/user-attachments/assets/ca059bcd-1b6b-426d-be83-3f74575142fb" />


# Result:
Thus, all the data visualization techniques of seaborn has been implemented.
