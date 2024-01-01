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

def max_marks(marks):

    marks.sort()
    
    return marks[-1]
    

ii)	# To find the maximum marks using the list method max().

def max_marks(marks):

    max(marks)
    
    return max(marks)
    
    
iii) # To find the maximum marks without using builtin functions.

def max_marks(list1):

    highest=list1[0]
    
    for i in range(1,len(list1)):
    
        if list1[i]>highest:
        
           highest=list1[i]
           
    return highest  
    

## Sample Input and Output
![output](./img/max_marks1.jpg) 
i)	# To find the maximum of marks using the list method sort.


## Output:![Screenshot 2024-01-01 115212](https://github.com/23004345/FindMaximum/assets/138849203/717527de-5b0b-4b29-83a2-290814256b95)

ii)	# To find the maximum marks using the list method max().

![Screenshot 2024-01-01 115225](https://github.com/23004345/FindMaximum/assets/138849203/86063975-551f-47a3-b9e2-8b0ba2b29ad0)

iii) # To find the maximum marks without using builtin functions.

![Screenshot 2024-01-01 115239](https://github.com/23004345/FindMaximum/assets/138849203/5e840961-f481-4c27-8027-c8027dd61d63)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
