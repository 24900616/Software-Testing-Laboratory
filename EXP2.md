# Ex.No: 2   Matrix Multiplication 
### DATE: 20.03.2025                                                                         
### REGISTER NUMBER : 212224260284

### AIM: 
Write a python program for matrix multiplication and inspect for failures.
 
### Algorithm:

1. Start the program.
2. Create empty list formatrix1, matrix2 and result.
3. Get the rows and columns count from the user.
4. Get the values of two matrix.
5. Perform matrix multiplication and store the answer in result.
6. Stop the program.

### Program:
```
r1, c1 = input("Enter row and column count in matrix 1: ").split()
r2, c2 = input("Enter row and column count in matrix 2: ").split()

matrix1 = []
matrix2 = []
result = []

if r1.isnumeric() and c1.isnumeric() and r2.isnumeric() and c2.isnumeric():
    r1 = int(r1)
    c1 = int(c1)
    r2 = int(r2)
    c2 = int(c2)

    if c1 != r2:
        print("Matrix multiplication not possible")
    elif max(r1, c1, r2, c2) > 20 or min(r1, c1, r2, c2) == 0:
        print("Matrix multiplication not possible")
    else:
        for i in range(r1):
            a = []
            for j in range(c1):
                a.append(int(input("<-- ")))
            matrix1.append(a)

        for i in range(r2):
            a = []
            for j in range(c2):
                a.append(int(input("<-- ")))
            matrix2.append(a)

        for i in range(r1):
            inter = []
            for j in range(c2):
                sum = 0
                for k in range(r2):
                    sum += matrix1[i][k] * matrix2[k][j]
                inter.append(sum)
            result.append(inter)

        for i in range(r1):
            for j in range(c2):
                print(result[i][j], end=" ")
            print()

else:
    print("Enter a valid number")
```

### Output:

  ![1 (2)](https://github.com/user-attachments/assets/fa93c838-bfb8-4931-a62b-bb8fb350a294)
  ![2 (2)](https://github.com/user-attachments/assets/1f45e262-153a-40b3-8e38-3ad98196d9b3)
  ![3 (3)](https://github.com/user-attachments/assets/394c0205-6ae3-43d6-a144-d1c3d43ae8c0)
  ![4 (3)](https://github.com/user-attachments/assets/fc411d4d-8815-4edf-b1c3-ae5d207adfc8)
  ![5 (3)](https://github.com/user-attachments/assets/c8c6b92c-339c-41ba-9b6b-7c64fb4f418a)
  ![6a](https://github.com/user-attachments/assets/d84e9fe0-4dec-4827-86e5-b07315fd659b)
  ![6b](https://github.com/user-attachments/assets/e3706112-d171-421c-a616-7773c528bf5d)
  ![7a](https://github.com/user-attachments/assets/c1203e7e-11ef-422c-8560-22a724316367)
  ![7b](https://github.com/user-attachments/assets/1233f791-b892-4ed6-88e4-e75f868d31f9)
  ![8 (2)](https://github.com/user-attachments/assets/df171d9d-cc6f-4bd1-95e6-f73dcc946e55)
  ![9 (2)](https://github.com/user-attachments/assets/57bd13d6-a11c-4317-abd3-0f62514cf82c)
  ![10a](https://github.com/user-attachments/assets/a8c61c35-1c14-4144-9fda-4573c8b0e219)
  ![10b](https://github.com/user-attachments/assets/a7bf674b-b6d7-459b-8b24-ac3189ae68f5)

### Result:
Thus, the python program for matrix multiplication is implemented and the causes for its failure is introspected successfully.

