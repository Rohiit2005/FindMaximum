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
## Output:
![exp3a(1)](https://github.com/Rohiit2005/FindMaximum/assets/138849178/0431f1bb-5ff7-4b06-b094-78850c6ac7b7)
![exp3a(2)](https://github.com/Rohiit2005/FindMaximum/assets/138849178/b5350ca8-0275-4d78-a937-bd0c0f68da12)
![exp3a(3)](https://github.com/Rohiit2005/FindMaximum/assets/138849178/eab8246b-cc5c-4253-bc14-efe50abbcdd1)





## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
