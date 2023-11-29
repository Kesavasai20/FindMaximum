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
Program to mark the maximum of marks using the list method sort
Developed by: K Kesava sai
RegisterNumber: 23002539

def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
   

```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by: K Kesava sai
RegisterNumber: 23002539

def max_marks(marks):
    large = max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by: K Kesava sai
RegisterNumber: 23002539

def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max        


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![3b-phy](https://github.com/Kesavasai20/FindMaximum/assets/138849303/ac9bd377-408b-40a2-bf83-1cbfa88b95fa)
![3b-phy2](https://github.com/Kesavasai20/FindMaximum/assets/138849303/53aad93d-9f6f-4264-ac47-57d90ddd3cd0)
![3b-phy3](https://github.com/Kesavasai20/FindMaximum/assets/138849303/191ee60a-fb94-4d89-910f-ae4da9a70700)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
