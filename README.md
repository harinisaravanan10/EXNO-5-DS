# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

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
 import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
```
LINE PLOT

```
marks=[13,45,63,78]
student=['ABC','QOR','EFB','TOB']
plt.plot(marks,student)
plt.xlabel('Marks')
plt.ylabel('Student name')
plt.show()
student=['A','B','C','D']
attendence=[90,85,73,88]
plt.plot(attendence,student)
plt.xlabel('Attendence')
plt.ylabel('Student name')
plt.show()
```

<img width="582" height="728" alt="504889840-cbda6d34-eace-430f-a1ee-279a57e77635" src="https://github.com/user-attachments/assets/ae019671-7907-4803-909d-9d138c702006" />


SCATTER PLOT

```
x=[10,20,30,40,50]
y=[100,200,300,400,500]
plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
plt.show()
x=np.arange(0,15)
y=np.arange(0,15)
x
y
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('y axis')
plt.title('Scatter plot')
plt.show()
```

<img width="579" height="740" alt="image" src="https://github.com/user-attachments/assets/1bbb484a-6bf8-4da2-8a6d-d34c30064b04" />

PIE PLOT

```
act=['eat','sleep','work','play']
slices=[3,7,8,6]
color=['r','y','g','b']
plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
feedback=['Good','excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```

<img width="565" height="695" alt="image" src="https://github.com/user-attachments/assets/e2594f98-f41d-4038-bc00-1dc005d053c4" />

AREA CHART

```
x = [1, 2, 3, 4, 5]
y1 = [10, 12, 14, 16, 18]
y2 = [5, 7, 9, 11, 13]
y3 = [2, 4, 6, 8, 10]
plt.fill_between(x, y1, color='blue')
plt.fill_between(x, y2, color='green')
plt.plot(x, y1, color='red')
plt.plot(x, y2, color='black')
plt.legend(['y1','y2'])
plt.show()
```

<img width="525" height="345" alt="image" src="https://github.com/user-attachments/assets/3e80665e-df38-4f90-bfe4-ff3331178afc" />

BAR CHART

```
height = [10, 24, 36, 40, 5]
names = ['one', 'two', 'three', 'four', 'five']
c1=['red', 'green'] 
c2=['b', 'g']
plt.bar (names, height, width=0.8, color=c1)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My bar chart!')
plt.show()
```

<img width="579" height="395" alt="image" src="https://github.com/user-attachments/assets/b3bd4224-fe22-4699-8a35-fd3e4f3694b4" />

HISTOGRAM

```
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='blue', alpha=0.5)
plt.show()
```

<img width="556" height="364" alt="image" src="https://github.com/user-attachments/assets/67ff2113-fbdc-4dba-ab22-f73fa208bbc2" />

BOX PLOT

```
np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)
data
```

<img width="589" height="296" alt="image" src="https://github.com/user-attachments/assets/6d715701-719c-4b3f-ae24-f88a6fad1dd9" />

```
fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```

<img width="591" height="397" alt="image" src="https://github.com/user-attachments/assets/a0d2569e-5ecd-414b-bc37-a815ad6e5f4d" />


# Result:
 Thus, all the data visualization techniques of matplotlib has been implemented.
