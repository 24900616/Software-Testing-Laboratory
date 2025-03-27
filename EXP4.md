# Ex.No: 4 check the given number is Armstrong number or not and inspect for failures.
### DATE:  27.3.25                                                                          
### REGISTER NUMBER : 212224230284
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
```
x = input("Enter the input: ")
if x.isnumeric():
    x = int(x)
    temp = x
    cube = 0
    while temp > 0:
        digit = temp % 10
        cube = cube + (digit ** 3)
        temp //= 10

    if cube == x:
        print("Armstrong Number")
    else:
        print("Not Armstrong Number")
else:
    print("Enter a Positive Integer.")
```

### Output:

 ![stl20](https://github.com/user-attachments/assets/16273d1c-7da4-4fde-a1f7-f732490d4597)
 ![stl21](https://github.com/user-attachments/assets/423fde92-bfc4-4238-93d4-f6a56d08d690)
 ![stl23](https://github.com/user-attachments/assets/6735840f-9a4d-43b9-89f8-681631dbc8e9)
 ![stl24](https://github.com/user-attachments/assets/65a1d33c-0efc-49ef-a5ce-9dc705db6a57)
 ![stl25](https://github.com/user-attachments/assets/297d0b7b-ea13-4dd8-8e7e-636757a13d13)
 ![stl26](https://github.com/user-attachments/assets/b53afc09-80b3-4ac4-b515-2478172be77c)
 ![stl27](https://github.com/user-attachments/assets/baddc95a-1a80-4dd6-b091-b17b286c8eb5)
 ![stl28](https://github.com/user-attachments/assets/ce55d0d2-f37a-410d-9159-52a4ad35d6be)
 ![stl29](https://github.com/user-attachments/assets/8ff22211-f08c-45d6-a752-b47d7cc9c978)
 ![stl30](https://github.com/user-attachments/assets/8282a6c0-3bca-41cf-a5c3-9214b3ca5793)


### Result:
Thus, the python program to check the number is Armstrong number or not implemented and the output is verified successfully.


