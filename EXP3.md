# Ex.No: 3 To check the number is prime or not and inspect for failures.
 
### DATE: 27.03.2025                                                                           
### REGISTER NUMBER : 212224230284
### AIM: 
Write a python program to check the number is prime or not and inspect for failures.
 
### Algorithm:
1. Start the program.
2. Get the number to be checked from the user.
3. If the number is less than or equal to 1, return "Not Prime".
4. If the number is 2, return "Prime".
5. Start the iteration from 3, For each iteration:
6. If the number is divisible by the current iteration value, return "Not Prime".
7. If the number is not divisible by any value from 2 to the square root, return "Prime".
8. Stop the program.

### Program:
```
num=input()
flag=0
if num.isnumeric():
  z=int(num)
  if z==2:
    flag=1
  if z>2:
    for i in range(2,z//2):
      if z%i==0:
        flag=0
        break
    else:
      flag=1
  if flag==1:
    print("Prime Number")
  else:
    print("Not a Prime Number")
else:
  print("Enter a positive number")
```
### Output:

![stl1](https://github.com/user-attachments/assets/26aa1ccd-bdc1-44ac-a4f2-28d1784f7a3e)
![stl2](https://github.com/user-attachments/assets/4c22c800-9c58-4348-a245-da5a4139ca96)
![stl3](https://github.com/user-attachments/assets/0d5a8fd8-025a-488b-bff4-4152806f8515)
![stl4](https://github.com/user-attachments/assets/f23536aa-c38e-41b9-aa9c-cc80f4dd2aa5)
![stl5](https://github.com/user-attachments/assets/13a60099-6764-4885-83bc-dc73f88734b1)
![stl6](https://github.com/user-attachments/assets/aa4c2e3f-c9dd-46e2-9581-38b661585d2b)
![stl7](https://github.com/user-attachments/assets/03f02a24-abc9-4fb3-8196-0f3fa54a4d32)
![stl8](https://github.com/user-attachments/assets/cb94bcd5-11da-4eb9-8d0c-8090ed95f264)
![stl9](https://github.com/user-attachments/assets/57ef94b4-d941-4bea-9295-2ed4ecf83182)
![stl10](https://github.com/user-attachments/assets/43299a83-03d3-4d1d-9b88-d6b8eeb18dfb)

### Result:
Thus, the python program to check the number is prime or not is implemented and the output is verified successfully.
