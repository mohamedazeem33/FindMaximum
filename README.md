# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

#step 1:
Get the list of marks as input

#step 2:
Use the sort() function or max() function or use the for loop to find the maximum mark.

#step 3:
Return the maximum value

## Program:

i)	# To find the maximum of marks using the list method sort.
#Developed by :   MOHAMED AZEEM N
#Reference no :   22007405
```Python
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    max=marks[0]
    for i in marks:
        if i>max:
           max=i
max_marks([88,67,77,93,95,11,67,89,56,89])

```

iii) # To find the maximum marks without using builtin functions.
```Python

def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
max_marks([88,67,77,93,95,11,67,89,56,89])

```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
#PROGRAM 1

![Screenshot (27) new](https://user-images.githubusercontent.com/121040764/214806397-862636e0-24b5-4e8f-bb2a-550b638975ae.png)

#PROGRAM 2
![Screenshot (28) new](https://user-images.githubusercontent.com/121040764/214807051-6e7baddb-3e26-40a8-9004-1611f1c9b9ca.png)

#PROGRAM 3
![Screenshot (29) new](https://user-images.githubusercontent.com/121040764/214807073-ab64137c-ee83-45c8-941d-09c02c1ff4b6.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
