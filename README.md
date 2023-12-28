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

i)	# To find the maximum of marks using the list method sort.
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Rohiit.A.S
RegisterNumber:23010688 
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Rohiit.A.S
RegisterNumber:23010688 
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Rohiit.A.S
RegisterNumber: 23010688
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![exp3a(1)](https://github.com/Rohiit2005/FindMaximum/assets/138849178/a2931d65-0420-4046-9c62-cab7f600d941)
![exp3a(2)](https://github.com/Rohiit2005/FindMaximum/assets/138849178/fe2c89a7-4e4c-42bd-a8b5-08a85f363e52)
![exp3a(3)](https://github.com/Rohiit2005/FindMaximum/assets/138849178/c6048438-7505-4afa-bfe9-2a4101e8dad5)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
