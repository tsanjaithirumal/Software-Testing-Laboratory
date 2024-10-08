# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:  24-09-24                                                                          
### REGISTER NUMBER : 212222040145

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:

```py
def display(): 
    start = input("Enter a positive value for START: ") 
    end = input("Enter a positive value for END: ") 
    
    if start.isnumeric() and end.isnumeric(): 
        start = int(start) 
        end = int(end)
        
        while True: 
            print(start, end=' ')
            
            if start < end: 
                start += 1 
            else: 
                break 
    else: 
        print("Enter a valid positive number.") 

display()



start = input("Enter a positive value for START: ")
end = input("Enter a positive value for END: ")

if start.isnumeric() and end.isnumeric():
    start = int(start)
    end = int(end)
    
    while start < end:
        print(start)
        start += 1
else:
    print("Enter a valid positive number.")


def switch(): 
    switcher = { 
        0: "even", 
        1: "odd" 
    }
    
    n = input('Enter a value for N: ')
    
    try: 
        n = int(n) 
        print(switcher[n % 2]) 
    except ValueError: 
        print("Enter a valid number.") 

switch()


def compare(): 
    a = input("Enter a value for A: ") 
    b = input("Enter a value for B: ") 
    
    try: 
        a = int(a) 
        b = int(b) 
        
        if a > b: 
            print("A is greater than B") 
        elif a < b: 
            print("B is greater than A") 
        else: 
            print("A is equal to B") 
    
    except ValueError: 
        print("Enter a valid number.")

compare()


def iterate(): 
    string = input("Enter a string: ") 
    for i in string: 
        print(ord(i), end=" ") 

iterate()

```














### Output:
![WhatsApp Image 2024-08-27 at 13 38 16_ee6fa658](https://github.com/user-attachments/assets/d8be6d66-02ea-4661-815a-12d975b422bf)


![WhatsApp Image 2024-08-27 at 13 44 27_84a0d22f](https://github.com/user-attachments/assets/b529ab1c-1224-435e-9f8b-7ee4385db4b3)


![WhatsApp Image 2024-08-27 at 13 49 05_7566a56a](https://github.com/user-attachments/assets/1c0d2fba-671d-46aa-b454-45b996f15308)

![WhatsApp Image 2024-08-27 at 13 52 49_23f8a623](https://github.com/user-attachments/assets/6f64c5b5-67cf-4538-b3bc-48cd460c34ff)


### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.
