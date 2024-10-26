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
NAME:NAGALAPURAM HASIF
REG:212223100036
def max_marks(marks):
    marks.sort() 
    large = marks[-1]
    return large



```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    large = max(marks)
    return large
    


```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(marks):
    max=marks[0]
    for i in marks:
        if i > max:
            max=i
    return max


```

## Output:
![Screenshot 2024-10-26 162412](https://github.com/user-attachments/assets/5c02c2fe-5eee-49ac-b457-2af971c48721)
![Screenshot 2024-10-26 162445](https://github.com/user-attachments/assets/fd5f13b3-2ac9-4f9e-bd89-573623b6df9f)
![Screenshot 2024-10-26 162511](https://github.com/user-attachments/assets/7c672ba0-36ae-4bfe-9026-9b3b76d237fe)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
