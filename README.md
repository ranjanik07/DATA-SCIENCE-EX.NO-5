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
<img width="847" height="329" alt="image" src="https://github.com/user-attachments/assets/0338b8e5-f38c-4faa-a8ab-010e9d3bf9fa" />
<img width="842" height="340" alt="image" src="https://github.com/user-attachments/assets/cf7e7526-c745-433c-bcc1-b50ae7d6d48d" />

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
<img width="832" height="311" alt="image" src="https://github.com/user-attachments/assets/8f6969f4-3cd0-417b-9204-acd4f7eb0e3c" />
<img width="838" height="346" alt="image" src="https://github.com/user-attachments/assets/98d7aba8-6617-466d-84e1-35b4dacea1f8" />

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
<img width="837" height="314" alt="image" src="https://github.com/user-attachments/assets/ce9c5c6a-95fb-4ce1-80b0-351fb26d11bc" />
<img width="830" height="304" alt="image" src="https://github.com/user-attachments/assets/aafb8077-b28d-4085-8981-9ce25df1312b" />

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
<img width="844" height="317" alt="image" src="https://github.com/user-attachments/assets/1a9915e6-dbcc-475a-a9f9-b6b26cd2872e" />

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
<img width="841" height="347" alt="image" src="https://github.com/user-attachments/assets/9eba548c-b63d-4290-af1d-aa4ad6c920ac" />

```
#Histogram: 
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1] 
plt.hist(x, bins = 10, color='blue', alpha=0.5) 
plt.show()
```
<img width="837" height="317" alt="image" src="https://github.com/user-attachments/assets/9c70e4f2-5471-41d0-86a2-ea9421a42c30" />

```
#Box Plot: 
np.random.seed(0) 
data=np.random.normal(loc=0, scale=1, size=100) 
data
```
<img width="827" height="267" alt="image" src="https://github.com/user-attachments/assets/45677a29-6510-4237-8240-425285e0d145" />

```
fig, ax= plt.subplots() 
ax.boxplot(data) 
ax.set_xlabel('Data') 
ax.set_ylabel('Values') 
ax.set_title('Box Plot')
```

<img width="842" height="349" alt="image" src="https://github.com/user-attachments/assets/de8d09dc-1f09-4702-a01b-c06f6a674a39" />


# Result:
 Thus, all the data visualization techniques of matplotlib has been implemented.
