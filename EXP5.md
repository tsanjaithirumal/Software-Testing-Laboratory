# Ex.No: 5 Binary Search.
### DATE: 01-10-24                                                                       
### REGISTER NUMBER : 212222040145


### AIM: 
Write a python program for Binary Search and inspect for failures.

### Algorithm:
1. Start the program. 
2. Get the list from the user 
3. Get the element to be searched 
4. Compare the mid element with the key, if same return the index 
5. If key is greater, search it in the right side, else search it in the left side. 
6. If not found return -1 
7. Stop the program.

### Program:

```py
def binary_search(arr, x):
    low = 0
    high = len(arr) - 1

    while low <= high:
        mid = (high + low) // 2
        
        # Check if x is present at mid
        if arr[mid] < x:
            low = mid + 1
        elif arr[mid] > x:
            high = mid - 1
        else:
            return mid  # Return the index of the element if found
    
    return -1  # Return -1 if the element is not found

arr = [2, 3, 4, 10, 40]
x = input("Enter the element to be searched: ")

try:
    x = int(x)
    result = binary_search(arr, x)
    if result != -1:
        print("Element is present at index", str(result))
    else:
        print("Element is not present in array")
except ValueError:
    print("Enter a valid integer input!")

```

### Output:

![WhatsApp Image 2024-10-01 at 13 26 03_cbf2c3b3](https://github.com/user-attachments/assets/8e87ec25-e091-44c4-8a48-a8548fc468a6)

### Result:
Thus, the python program of binary search is implemented and the output is verified successfully. 
