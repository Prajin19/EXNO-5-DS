# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY
## Name: Prajin S
## Register Number : 212223230151
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
```Python
import matplotlib.pyplot as plt
xvalues=[0,1,2,3,4,5]
yvalues=[0,1,4,9,16,25]
plt.plot(xvalues,yvalues)
plt.show()
```

![image](https://github.com/user-attachments/assets/711f790c-f2e6-4d58-9809-bf999da488e5)
```Python
x=[1,2,3]
y=[2,4,1]
plt.plot(x,y)
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('My first graph!')
plt.show()
```
![image](https://github.com/user-attachments/assets/063ed070-d137-49a7-b792-eb84514d135e)
```Python
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label="Line 1")
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label="Line 2")
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/7590381a-3e10-4c2a-b998-f9d71079ff70)
```Python
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.ylim(1,8)
plt.xlim(1,8)
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('Some cool customizations!')
plt.show()
```
![image](https://github.com/user-attachments/assets/b57e55a8-915a-4990-87a9-e73d570d59d9)
```Python
yieldapples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yieldapples)
```
![image](https://github.com/user-attachments/assets/f0ca53c1-6e0b-467e-81a5-491eaf44f135)

```Python
years=[2010,2011,2012,2013,2014,2015]
yieldapples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yieldapples)
```
![image](https://github.com/user-attachments/assets/4c1d15a5-001b-4fb1-93cf-960f522f6236)

```Python
year=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896]
plt.plot(year,apples)
plt.plot(year,oranges)
plt.xlabel('year')
plt.ylabel('Yield (tons per hectare)');
```
![image](https://github.com/user-attachments/assets/12ca4a80-73a8-4e40-b138-18e284de22a6)

```Python
plt.plot(year,apples)
plt.plot(year,oranges)
plt.xlabel('year')
plt.ylabel('Yield (tons per hectare)')
plt.title("Crop Yields in Kanto")
plt.legend(['Apples','oranges']);
```
![image](https://github.com/user-attachments/assets/8482cc18-b881-4321-9a72-9fa8486ef29a)

```Python
plt.plot(years,yieldapples)
plt.xlabel("Year")
plt.ylabel('yield(tons per hectare)');
```
![image](https://github.com/user-attachments/assets/525a6c02-3d2e-4a6e-a524-ec803868c5cf)

```Python
plt.figure(figsize=(12,6))
plt.plot(year,oranges,marker='o')
plt.title("Yield of Oranges (tons per hectare)");
```
![image](https://github.com/user-attachments/assets/ff883385-f909-46ae-beb7-587f6653a770)

```Python
plt.plot(year,apples,marker='o')
plt.plot(year,oranges,marker='x')
plt.xlabel("Year")
plt.ylabel('Yield (tons per hectare)')
plt.title("Crop Yields in Kanto")
plt.legend(['Apples','oranges'])
```
![image](https://github.com/user-attachments/assets/71c08fa8-31b6-4ef3-ac5e-e29c5b97208e)

```Python
plt.scatter(xvalues,yvalues,s=30,color="blue")
plt.show()
```
![image](https://github.com/user-attachments/assets/ccebdbee-94da-41f4-a610-3e8bdcc0e144)

```Python
x2=[1,2,3,4,5,6,7,8,9,10]
y2=[2,4,5,7,6,8,9,11,12,12]
plt.scatter(x2,y2,s=30,label="stars",color="green",marker="*")
plt.xlabel("X-axis")
plt.ylabel("Y-axis")
plt.title("My Scatter Plot!")
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/8737868b-1f82-4672-a094-f62e3e86bbb6)

```Python
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x
```
![image](https://github.com/user-attachments/assets/8a2eabe7-9444-4885-ba5c-911b3fe88ad4)

```Python
y
```
![image](https://github.com/user-attachments/assets/57082887-73ff-49c1-b882-b5d0771c13f6)

```Python
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```
![image](https://github.com/user-attachments/assets/59661c4a-e472-414f-b0e4-f3a5603972b3)

```Python
y=x*x
y
```
![image](https://github.com/user-attachments/assets/8be13c51-9d55-4768-994a-59f157f8c774)

```Python
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.title('2D Diagram')
plt.ylabel('Y axis')
plt.xlabel('X axis')
```
![image](https://github.com/user-attachments/assets/56854db6-cd85-4c9f-b9df-e2cca009c69c)

```Python
plt.subplot(2,2,1)
plt.plot(x,y,'r--')
plt.subplot(2,2,2)
plt.plot(x,y,'g*--')
plt.subplot(2,2,3)
plt.plot(x,y,'bo')
plt.subplot(2,2,4)
plt.plot(x,y,'go')
```
![Screenshot 2024-10-22 091438](https://github.com/user-attachments/assets/2a981bad-c59d-45c0-8042-e8582bfafb3d)

```Python
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("Sine Waveform")
plt.plot(x,y)
plt.show()
```
![Screenshot 2024-10-22 091509](https://github.com/user-attachments/assets/90832a26-f60c-4f77-90bf-8d1153740265)

```Python
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')
plt.plot(x,y1,color='red')
plt.plot(x,y2,color='black')
plt.legend(['y1','y2'])
plt.show()
```
![image](https://github.com/user-attachments/assets/70fd3192-76a0-433d-b2c6-17292ff62548)

```Python
plt.stackplot(x,y1,y2,y3,labels=['Line 1','Line 2','Line 3'])
plt.legend(loc='upper left')
plt.title('Stacked Line Chart')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.show()
```
![image](https://github.com/user-attachments/assets/5ad74511-615c-4b85-b8a8-61d1907f8e87)

```Python
from scipy.interpolate import make_interp_spline
x=np.array([1,2,3,4,5,6,7,8,9,10])
y=np.array([2,4,5,7,8,8,9,10,11,12])
spl=make_interp_spline(x,y)
x_smooth=np.linspace(x.min(),x.max(),100)
y_smooth=spl(x_smooth)
plt.plot(x,y,'o',label='data')
plt.plot(x_smooth,y_smooth,label='Spline')
plt.legend(loc='best')
plt.show()
```
![image](https://github.com/user-attachments/assets/1484cb0e-653c-4a47-9b58-eae4bff40c07)

```Python
values=[5,6,3,7,2]
names=["A","B","C","D","E"]
plt.bar(names,values,color="green")
plt.show()
```
![image](https://github.com/user-attachments/assets/69e4c6b0-aada-47c3-aeb3-497ca579e97c)

```Python
values=[5,6,3,7,2]
names=["A","B","C","D","E"]
plt.barh(names,values,color="yellowgreen")
plt.show()
```
![image](https://github.com/user-attachments/assets/60ebad0d-a351-4473-8cbc-0fc1c69e41fe)

```Python
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,color=c1,width=0.8)
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('My bar chart!')
plt.show()
```
![image](https://github.com/user-attachments/assets/0e5f2401-ccba-4a18-bcdb-7360a1244b8e)

```Python
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar Graph')
plt.ylabel('Y-axis')
plt.xlabel('X-axis')
plt.show()
```
![image](https://github.com/user-attachments/assets/21d70c4a-fb60-4d5c-b14d-0398f443aafd)

```Python
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('Age')
plt.ylabel('No. of people')
plt.title('My Histogram')
plt.show()
```
![image](https://github.com/user-attachments/assets/7b1e8add-cd41-4288-a6da-289b71d68116)

```Python
x=[2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x,bins=10,color='blue',alpha=0.5)
plt.show()
```
![image](https://github.com/user-attachments/assets/0194075b-b12a-423c-9f99-1bc56d4c1ea1)

```Python
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
![image](https://github.com/user-attachments/assets/6d028222-e046-4258-8c59-4b5c405432a6)

```Python
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_xlabels('Boxplot')
```
![image](https://github.com/user-attachments/assets/dde959d2-1c05-4544-a436-d51a7ec6ae96)

```Python
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/fdd5d06d-5619-4ff4-8de3-146a1849dbf2)

```Python
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```
![image](https://github.com/user-attachments/assets/66233fed-1281-4ac1-aef5-6c037b34916c)


# Result:
Data Visualization is performed using matplot python library for the given datas.
