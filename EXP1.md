# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:                                                                            
### REGISTER NUMBER : 212224230284

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

1.do..While:
```
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
        print("Please enter valid positive numbers.")

display()
```
2.while..do:
```
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
```
3.switch:
```
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
```
4.if..else:
```
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
```
5.for:
```
def iterate():
    string = input("Enter a string: ")
    for i in string:
        print(ord(i), end=" ")

iterate()
```
### Output:
1.do..while

![1st](https://github.com/user-attachments/assets/5e008c37-a66b-4178-b8fd-229d19125aa0)
![1st output](https://github.com/user-attachments/assets/33f27e90-87e3-4a54-971c-38b7f0e7c5d5)

2.while..do

![2 a](https://github.com/user-attachments/assets/028bdd6c-8f7a-4c8b-85c6-c10c35de15a3)
![2b](https://github.com/user-attachments/assets/5464c1df-2bc6-4283-b4a4-d1761dc21255)
![2c](https://github.com/user-attachments/assets/17569ddd-1c65-4729-87a8-7e59d092cc4c)
![WhatsApp Image 2025-03-13 at 03 39 00_362d1973](https://github.com/user-attachments/assets/184d257d-0d95-4fe9-a7b6-e4eb797b928c)
![WhatsApp Image 2025-03-13 at 03 47 17_096a9332](https://github.com/user-attachments/assets/50093ac0-41ee-4122-88ad-27955479eae3)

3.switch

![3 (2)](https://github.com/user-attachments/assets/7d86c20b-573b-45b6-a440-d8498d50be3d)

4.if..else

![4 (2)](https://github.com/user-attachments/assets/af287ea7-5ff2-4cbc-8b8d-bb0d48f9387b)
![4 output](https://github.com/user-attachments/assets/3c177146-c652-4b13-aac9-498daa1bfba1)

5.for

![5 (2)](https://github.com/user-attachments/assets/516bbae4-9e66-4b5c-bada-6ad8db363f21)

















### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


