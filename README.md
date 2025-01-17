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
```
Developed by:thrikeswar
RegisterNumber:2122222230162
def max_marks(marks):
    marks.sort()
    b=marks[-1]
    return b
```
ii)	# To find the maximum marks using the list method max().
```
Developed by:thrikeswar
RegisterNumber:2122222230162 
def max_marks(marks):
    a=max(marks)
    return a
```
iii) # To find the maximum marks without using builtin functions.
```
Developed by:thrikeswar
RegisterNumber:2122222230162 
def max_marks(list1):
    for i in list1:
        if i>94:
            return i
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 
## Output:
i)	# To find the maximum of marks using the list method sort.

<br>![output](./ex3a(a)(p).png)
ii)	# To find the maximum marks using the list method max().
<br>![output](./ex2a(b)(p).png)
iii) # To find the maximum marks without using builtin functions.
<br>![output](./ex3a(c)(p).png)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
