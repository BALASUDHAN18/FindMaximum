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
Developed by: BALASUDHAN P
RegisterNumber: 212222240017
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
Developed by: BALASUDHAN P
RegisterNumber: 212222240017
'''
def max_marks(marks):
    large = max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python

''' 
Program to the maximum marks without using builtin functions.
Developed by: BALASUDHAN P
RegisterNumber: 212222240017
'''
def max_marks(list1):
    max= list1[0]
    for i in list1:
        if i > max:
            max = i
    return max       
```
## Output:
![243067652-27b0e532-fb0e-4405-8658-b09aa70681a3](https://github.com/BALASUDHAN18/FindMaximum/assets/118807740/ec4a2bff-2a13-4641-b060-4c3ccac86d48)

![243067708-e9de80be-a4f2-4e2b-a778-77a0335a1374](https://github.com/BALASUDHAN18/FindMaximum/assets/118807740/ef022e0b-5c1f-41a3-b575-7bd6ad3e7762)

![243067775-7e498bc0-fe4d-47c2-a311-11a755e01daa](https://github.com/BALASUDHAN18/FindMaximum/assets/118807740/41e1c912-f54b-4cc3-9754-d9b51c9aefcb)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
