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
NAME: VANISHAA HARSHINI.B.R
REG NO: 212225040481
```

```
import pandas as pd 
import numpy as np 
import seaborn as sns 
import matplotlib.pyplot as plt 
#Line Plot: 
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

<img width="873" height="736" alt="image" src="https://github.com/user-attachments/assets/03082d54-69b8-418c-86ef-67fd92d89979" />

```
#Scatter Plot: 
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

<img width="802" height="736" alt="image" src="https://github.com/user-attachments/assets/f356b028-d9e7-4716-beb8-ee3fd53e4757" />

```
#Pie Chart: 
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

<img width="685" height="701" alt="image" src="https://github.com/user-attachments/assets/12d429c6-ebbc-4d3d-a2cb-aa0024379405" />


```
#Area Chart: 
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

<img width="871" height="352" alt="image" src="https://github.com/user-attachments/assets/8a7a7d8b-755b-4df2-8804-5e5779764b6d" />


```
#Bar Chart: 
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

<img width="750" height="388" alt="image" src="https://github.com/user-attachments/assets/634c341b-3e6c-4494-b9d0-11756c00414d" />

```
#Histogram: 
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1] 
plt.hist(x, bins = 10, color='blue', alpha=0.5) 
plt.show()
```

<img width="717" height="358" alt="image" src="https://github.com/user-attachments/assets/a3ad668c-7688-4d02-97cc-14157cff9f55" />

```
#Box Plot: 
np.random.seed(0) 
data=np.random.normal(loc=0, scale=1, size=100) 
data
```

<img width="752" height="297" alt="image" src="https://github.com/user-attachments/assets/89b293b5-cda2-4971-adcb-82a88c1b423c" />

```
fig, ax= plt.subplots() 
ax.boxplot(data) 
ax.set_xlabel('Data') 
ax.set_ylabel('Values') 
ax.set_title('Box Plot')
```


<img width="891" height="398" alt="image" src="https://github.com/user-attachments/assets/60dac2f4-a7ee-46e7-82b1-23047d4a3215" />




# Result:
Thus, all the data visualization techniques of matplotlib has been implemented.
