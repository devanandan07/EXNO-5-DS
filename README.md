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
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
```
```
x_values= [0,1,2,3,4,5]
y_values= [0,1,4,9,16,25]
plt.plot(x_values,y_values)
plt.show()
```

![image](https://github.com/user-attachments/assets/a40c99b8-a17a-4b47-a6e8-b005d916e275)

```
x=[1,2,3]
y=[2,4,1]
plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My first graph!')
plt.show()
```

![image](https://github.com/user-attachments/assets/910fa222-e012-453b-92d0-3ad258f23e59)

```
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1, y1 ,label="line 1")
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2, y2 ,label="line 2")
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()
```

![image](https://github.com/user-attachments/assets/f251d902-14c1-46d5-b1f6-bca2ceadef60)

```
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.ylim(1,8)
plt.xlim(1,8)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations!')
plt.show()
```

![image](https://github.com/user-attachments/assets/9a127a7a-3f10-4f92-a874-afd6a353d50f)

```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)

```

![image](https://github.com/user-attachments/assets/9a9fbbe0-5710-429f-9103-5004bd987b10)

```
years=[2010,2011,2012,2013,2014,2015]
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)
```

![image](https://github.com/user-attachments/assets/9155efaa-60c0-4510-b529-b1dc9319b08a)

```
year=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.962,0.941,0.930,0.923,0.918,0.988,0.907,0.984,0.901,0.898,0.9,0.896, ]
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yield(tons per hectare)');
```

![image](https://github.com/user-attachments/assets/43b61df2-aa10-4d85-b4cb-50997b33e2c0)

```
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yield(tons per hectare)')
plt.title("Crop yield in Kanto")
plt.legend(['apples','oranges'])
```

![image](https://github.com/user-attachments/assets/f3f353e5-d694-4d1b-8cfa-3e410d243bd7)

```
plt.plot(years, yield_apples)
plt.xlabel('Year')
plt.ylabel('Yield(tons per hectare)');
```

![image](https://github.com/user-attachments/assets/58cebe83-ec8f-45cc-a518-99e8026489ae)

```
plt.figure(figsize=(12,6))
plt.plot(year, oranges, marker='o')
plt.ylabel('Yield of oranges(tons per hectare)');
```

![image](https://github.com/user-attachments/assets/a5ab4409-93ae-4d89-a929-563275e3ae57)


```
plt.plot(year,apples,marker='o')
plt.plot(year,oranges,marker='x')
plt.xlabel('Year')
plt.ylabel('Yield(tons per hectare)')
plt.title("Crop yield in Kanto")
plt.legend(['apples','oranges'])
```

![image](https://github.com/user-attachments/assets/16ef15b5-1d82-4ee6-ba90-52f5198dfa56)

```
import matplotlib.pyplot as plt
x_values= [0,1,2,3,4,5]
y_values= [0,1,4,9,16,25]
plt.scatter(x_values,y_values,s=30,color="blue")
plt.show()
```

![image](https://github.com/user-attachments/assets/305553e8-3bc1-44bf-8f74-19688a0d59b8)


```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6,7,8,9,10]
y=[2,4,5,7,6,8,9,11,12,12]
plt.scatter(x,y,label="stars",color="green", marker="*", s=30)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My Scatter Plot!')
plt.legend()
plt.show()
```

![image](https://github.com/user-attachments/assets/cf277972-427e-4a2a-bb67-55fadeae6ffb)

```
x=np.arange(0,10)
y=np.arange(11,21)
```

```
x
```

![image](https://github.com/user-attachments/assets/89e15e9e-740a-4f32-8488-f000e53fae3a)

```
y
```

![image](https://github.com/user-attachments/assets/7ad4fe99-36a0-43c7-b9b8-f589c16b231c)

```
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```

![image](https://github.com/user-attachments/assets/a43d3c4c-0a03-4318-83d0-586aa729b317)

```
y=x*x
y
```

![image](https://github.com/user-attachments/assets/e5ccef80-8ef4-45eb-bc7a-e487aa9dfb31)

```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('X axis')
```

![image](https://github.com/user-attachments/assets/23eb97a4-30c2-4bd5-939d-ca3570b42c93)

```
plt.subplot(2,2,1)
plt.plot(x,y,'r--')
plt.subplot(2,2,2)
plt.plot(x,y,'g*--')
plt.subplot(2,2,3)
plt.plot(x,y,'bo')
plt.subplot(2,2,4)
plt.plot(x,y,'go')
```

![image](https://github.com/user-attachments/assets/edcc91ba-da66-4a46-a1a3-e219c9c88807)

```
np.pi
```

![image](https://github.com/user-attachments/assets/21ac17c5-b18b-4a94-a536-87cee95b0eca)

```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```

![image](https://github.com/user-attachments/assets/cb7e058a-8cce-4201-ac7b-3f89622dbaf2)

```
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')
plt.plot(x,y1,color='red')
plt.plot(x,y2,color='red')
plt.legend(['y1','y2'])
plt.show()
```

![image](https://github.com/user-attachments/assets/598a0ca0-991a-4555-ab0c-a3ef6208d9b3)

```
plt.stackplot(x,y1,y2,y3,labels=['Line 1','Line 2','Line 3'])
plt.legend(loc='upper left')
plt.title('Stacked Line Chart')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.show()
```

![image](https://github.com/user-attachments/assets/4a8e69d8-3026-407c-b767-8f4e0e2a2e2f)

```
import numpy as np
import matplotlib.pyplot as plt
from scipy.interpolate import make_interp_spline
x=np.array([1,2,3,4,5,6,7,8,9,10])
y=np.array([2,4,5,7,8,8,9,10,11,12])
spl=make_interp_spline(x,y)
x_smooth=np.linspace(x.min(),x.max(),100)
y_smooth=spl(x_smooth)
plt.plot(x,y,'o',label='data')
plt.plot(x_smooth,y_smooth,'-',label='spline')
plt.legend()
plt.show()
```

![image](https://github.com/user-attachments/assets/b1a945fd-f5e1-4b1d-a161-c090361fba05)

```
import matplotlib.pyplot as plt
values=[5,6,3,7,2]
names=["A","B","C","D","E"]
plt.bar(names,values,color="green")
plt.show()
```

![image](https://github.com/user-attachments/assets/ea845808-0531-4f3b-af38-b85bd9980541)

```
values=[5,6,3,7,2]
names=["A","B","C","D","E"]
plt.barh(names,values,color="yellowgreen")
plt.show()
```

![image](https://github.com/user-attachments/assets/f49f9a53-cc57-41d4-a97c-9b38e95c2bed)

```
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x-a')
```

![image](https://github.com/user-attachments/assets/247aa260-0e8b-4c96-9711-66f5b3ff1056)

```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar Graph')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.show()
```

![image](https://github.com/user-attachments/assets/08b6b16b-d385-42c6-8029-732eafc38c2e)

```
import matplotlib.pyplot as plt
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins = 10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No.of people')
plt.title('My histogram')
plt.show()
```

![image](https://github.com/user-attachments/assets/ffd635c0-683d-4aec-9842-f206aff7006c)

```
x=[2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x,bins=10,color='blue',alpha=0.5)
plt.show()
```

![image](https://github.com/user-attachments/assets/3ed003da-28c2-44c7-a3e2-31ebf2d68239)

```
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```

![image](https://github.com/user-attachments/assets/ca8c60cb-5fb8-41d9-b32c-d3065af55036)

```
fig, ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box plot')
```

![image](https://github.com/user-attachments/assets/78bf4668-511a-4d6b-a29e-2ebc4501c6fe)

```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```

![image](https://github.com/user-attachments/assets/073bc749-c6d0-4c8e-8d64-5ce5229d1f3b)

```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```

![image](https://github.com/user-attachments/assets/a6d19909-c6be-45a8-ba3f-f4d7745644d2)

# Result:
 Thus the program to Perform Data Visualization using matplot python library for the given datas is been implemented.
