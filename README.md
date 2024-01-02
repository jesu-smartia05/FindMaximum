# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:
''' 
Program to the maximum marks without using builtin functions.
Developed by: JESU SMARTIA A
RegisterNumber: 212223110016

i)	# To find the maximum of marks using the list method sort.
```Python
def max_marks(marks):
    marks.sort()
    max=marks[-1]
    return max
```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    return max(marks)
```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max1=list1[0]
    for i in list1:
        if i>max1:
            max1=i
    return max1
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:

![Screenshot 2024-01-02 145005](https://github.com/jesu-smartia05/FindMaximum/assets/148514819/d4cb5ed9-a5c3-419b-a48b-bb0cec0377cc)

![Screenshot 2024-01-02 145259](https://github.com/jesu-smartia05/FindMaximum/assets/148514819/f798d894-aece-4142-a73e-ef74440e6e1c)

![Screenshot 2024-01-02 145443](https://github.com/jesu-smartia05/FindMaximum/assets/148514819/c8480865-6a8d-4e91-a6e6-48765d883e48)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
