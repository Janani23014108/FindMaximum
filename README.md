# Find the maximum of a list of numbers
Name:J.JANANI

Register No:212223230085

Department:B.Tech AIDS
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

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large



```

ii)	# To find the maximum marks using the list method max().
```Python

def max_marks(marks):
    large=marks[len(marks)-1]
    marks.sort(reverse=True)
    large=marks[0]
    return large

```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(marks):
    maxmark=0
    for i in marks:
        if i>maxmark:
            maxmark=i
    return maxmark


```



## Output:

i)


![exp6 1st](https://github.com/Janani23014108/FindMaximum/assets/146822085/5de03190-ca70-4036-8b7d-613a25623fbb)

ii)


![exp6 2](https://github.com/Janani23014108/FindMaximum/assets/146822085/d6fe1620-e2ad-4e5f-9fa1-dc4f4f6cc91a)



iii)




![exp6 3](https://github.com/Janani23014108/FindMaximum/assets/146822085/86f013ef-e48b-4638-8f57-a79d1320fbb1)






## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
