# Ex.No:  7 Sorting. 
### DATE: 24/09/2024                                                                          
### REGISTER NUMBER :  212222040109
### AIM: 
Write a python program for sorting and inspect for failures. 
To write a python program for Fibonacci Series and test the test cases using Pytest.

### Algorithm:
1. Start
2. Get an input from the user by prompting 
3. Run a loop form 0 to len/2.
4. Check if the characters are the same both from the start and the end till len/2. 
5. If it is, return the result that it is a palindrome.
6. Else, return that it is not a palindrome. 
7. Stop the program.

### Program:
```
n = int(input("Enter the number of elements: "))  
arr = []  

try:  
    for i in range(n):  
        a = float(input("Enter the element: "))  
        arr.append(a)  
    
    for i in range(n):  
        for j in range(i + 1, n):  
            if arr[i] > arr[j]: 
                temp = arr[i] 
                arr[i] = arr[j] 
                arr[j] = temp 

    print("The array after sorting:") 
    for i in range(n): 
        print(arr[i], end=' ') 

except ValueError: 
    print("Enter a valid number")

```
### Output:
![Screenshot 2024-11-08 142107](https://github.com/user-attachments/assets/1abbf75c-e29a-4ba9-b272-fa5182146343)

### Result:
Thus, a program for binary search has been written and test cases have been written and verified successfully.
                           
