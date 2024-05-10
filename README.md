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
~~~
i)	# To find the maximum of marks using the list method sort.

# program to mark the maximum of marks using the list method sort.
#DEVELOPED BY: Vignesh S
#REGISTER NUMBER: 212223230240
def max_marks(array):
     array.sort()
     return array[-1]


ii)	# To find the maximum marks using the list method max().

#program to find the maximum marks using the list method max().
#DEVELOPED BY: Vignesh S
#REGISTER NUMBER:212223230240
def max_marks(array):
     return max(array)



iii) # To find the maximum marks without using builtin functions.

#program to find the maximum marks using the list method max().
#DEVELOPED BY: Vignesh S
#REGISTER NUMBER: 212223230240
def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1
~~~




## Output:

i)	# To find the maximum of marks using the list method sort.
![Screenshot 2024-05-10 181359](https://github.com/Vigneshvikiii/FindMaximum/assets/147474483/01921b82-dbe9-4e17-9969-097906530fe5)


ii)	# To find the maximum marks using the list method max().

![Screenshot 2024-05-10 181634](https://github.com/Vigneshvikiii/FindMaximum/assets/147474483/98c82fa0-35f7-47f8-b198-7a910bb5c456)

iii) # To find the maximum marks without using builtin functions.


![Screenshot 2024-05-10 181659](https://github.com/Vigneshvikiii/FindMaximum/assets/147474483/cd5adb84-4def-460a-ac7d-0f5790611431)






## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
