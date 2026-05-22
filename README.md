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
  import numpy as np
  import seaborn as sns
  import matplotlib.pyplot as plt

   marks=[13,45,63,78]
   student=['ABC','QOR','EFB','TOB']
   plt.plot(marks,student)
   plt.xlabel('Marks')
   plt.ylabel('Student name')
   plt.show()
```

<img width="1018" height="704" alt="image" src="https://github.com/user-attachments/assets/058f41b7-06bf-4c3a-9808-f838781039ad" />

```
  student=['A','B','C','D']
  attendence=[90,85,73,88]
  plt.plot(attendence,student)
  plt.xlabel('Attendence')
  plt.ylabel('Student name')
  plt.show()
```

<img width="1061" height="683" alt="image" src="https://github.com/user-attachments/assets/e06d8f7b-6e2b-455f-af1c-5f19a54c311f" />

```
 x=[10,20,30,40,50]
 y=[100,200,300,400,500]
 plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
 plt.show()
```

<img width="1046" height="653" alt="image" src="https://github.com/user-attachments/assets/b454173c-d50f-444f-9c71-b741ee46e7de" />

```
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

<img width="1103" height="796" alt="image" src="https://github.com/user-attachments/assets/c1e27ba9-14ff-475d-b48c-96d266cd3af9" />

```
 act=['eat','sleep','work','play']
 slices=[3,7,8,6]
 color=['r','y','g','b']
 plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()
```

<img width="1351" height="681" alt="image" src="https://github.com/user-attachments/assets/4a14104c-d485-4cd2-996d-f115c99438e1" />

```
feedback=['Good','excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```

<img width="1337" height="669" alt="image" src="https://github.com/user-attachments/assets/80537791-49d2-4309-b2ad-0dab3a687be2" />

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

<img width="1055" height="764" alt="image" src="https://github.com/user-attachments/assets/2a0cd465-d9cc-4395-8eee-f425765c0571" />

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


<img width="1032" height="781" alt="image" src="https://github.com/user-attachments/assets/c4c519da-9562-420d-90ca-b8a1edd9be87" />

```
 x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
 plt.hist(x, bins = 10, color='blue', alpha=0.5)
 plt.show()
```

<img width="1107" height="623" alt="image" src="https://github.com/user-attachments/assets/5479bdd8-f354-470d-a55a-b95eaeb4b8e6" />

```
 np.random.seed(0)
 data=np.random.normal(loc=0, scale=1, size=100)
 data
```

<img width="1040" height="540" alt="image" src="https://github.com/user-attachments/assets/545fb48b-5096-4ae3-88fe-368afbe6f27b" />

```
 fig, ax= plt.subplots()
 ax.boxplot(data)
 ax.set_xlabel('Data')
 ax.set_ylabel('Values')
 ax.set_title('Box Plot')
```


<img width="1026" height="729" alt="image" src="https://github.com/user-attachments/assets/e9dc8a8e-4fab-45ca-968c-6334fe987ce4" />


# Result:
Thus, all the data visualization techniques of matplotlib has been implemented.
