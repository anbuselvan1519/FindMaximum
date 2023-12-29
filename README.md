# Find the maximum of a list of numbers
### Name: Anbuselvan.S
### Reference No: 23005959
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
#Program to mark the maximum of marks using the list method sort
#Developed by: Anbuselvan.S
#RegisterNumber: 23005959

def max_marks(marks):
    marks.sort()
    return marks[-1]
```

ii)	# To find the maximum marks using the list method max().
```Python
#Program to find the maximum marks using the list method max().
#Developed by: Anbuselvan.S
#RegisterNumber: 23005959
def max_marks(marks):
    return max(marks)
```

iii) # To find the maximum marks without using builtin functions.
```Python
#Program to the maximum marks without using builtin functions.
#Developed by: Anbuselvan.S
#RegisterNumber: 23005959
def max_marks(list1):
    a=0
    for m in list1:
        if m>a:
            a=m
    return a 
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![image](https://github.com/anbuselvan1519/FindMaximum/assets/139841744/4b63327e-4c34-4008-bcb2-472ee6f20786)
![image](https://github.com/anbuselvan1519/FindMaximum/assets/139841744/b55e9a4d-ffcf-45ff-806d-6e14a2ee9931)
![image](https://github.com/anbuselvan1519/FindMaximum/assets/139841744/801fe6ee-2647-44f1-9c0b-99a2c2cb7b40)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
