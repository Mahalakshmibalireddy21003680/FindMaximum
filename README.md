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

i)	# To find the maximum of marks using the list method sort()
~~~
def max_marks(marks):
    a=max(marks)
    return a
~~~

ii)	# To find the maximum marks using the list method max().
~~~
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
~~~

iii) # To find the maximum marks without using builtin functions.
~~~
max_marks(list1):
    max_mark=0
    for i in list1:
        if i>max_mark:
            max_mark=i
    return max_mark
~~~
## Sample Input:
# To find the maximum of marks using the list method sort()
![GitHub Logo](s1.png)
# To find the maximum marks using the list method max().
![GitHub Logo](s2.png)
# To find the maximum marks without using builtin functions.
![GitHub Logo](s3.png)

## Output:
# To find the maximum of marks using the list method sort()
![GitHub Logo](sort1.png)
# To find the maximum marks using the list method max().
![GitHub Logo](max1.png)
# To find the maximum marks without using builtin functions.
![GitHub Logo](builtin1.png)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
