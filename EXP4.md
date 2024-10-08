# Ex.No: 4 check the given number is Armstrong number or not and inspect for failures.
### DATE: 01-10-2024                                                                       
### REGISTER NUMBER : 212222040145

### AIM: 
Write a python program to check the number is Armstrong number or not and inspect for failures.

### Algorithm:
1.  Start the program.
2.	Read an integer input number.
3.	Initialize the variables current_digit, sum = 0, and num = number.
4.	Repeat Steps 5 to 7 until num > 0
5.	current_digit = (num % 10).
6.	sum = sum + (current_digit * current_digit * current_digit). 7. Stop the program.
7.	num = num / 10.
8.	Check if sum == number. If true, print "It is an Armstrong Number." Otherwise, print "It is not an Armstrong Number."
9.	Stop the program.

### Program:

```py
lx = input("Enter the input: ")
if x.isnumeric():
    x = int(x)
    temp = x
    cube = 0
    while temp > 0:
        digit = temp % 10
        cube += digit ** 3
        temp //= 10
    if cube == x:
        print("Armstrong Number")
    else:
        print("Not Armstrong Number")
else:
    print("Enter a Positive Integer.")

```

### Output:

![WhatsApp Image 2024-10-01 at 13 27 17_5c1ed2b8](https://github.com/user-attachments/assets/fc7233da-aaaf-448b-b92c-965b23ea6e90)


### Result:
Thus, the python program to check the number is Armstrong number or not implemented and the output is verified successfully.
