# Ex.No: 6 To check whether the string is Palindrome and generate test cases.

### DATE: 17:04:25                                                                           
### REGISTER NUMBER : 212224230284
### AIM: 
Write a Python program to check whether the string is Palindrome and generate test cases. 
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
def Palindrome(string):
    for i in range(0, int(len(string) / 2)):
        if string[i] != string[len(string) - i - 1]:
            return False
    return True
s = input("Enter a string: ")
c = 1
for i in s:
    if not i.isalpha():
        c = 0
if c == 0:
    print("Enter a valid string")
else:
    answer = Palindrome(s)
    if answer:
        print("The given string is a palindrome")
    else:
        print("The given string is not a palindrome")
```
### Output:

![100](https://github.com/user-attachments/assets/c0d4123f-f74d-407d-a23d-f0a1961a50b1)
![101](https://github.com/user-attachments/assets/0ca39cac-6f92-4024-9263-bd74cb5c89d3)
![102](https://github.com/user-attachments/assets/bd6151e3-3a66-4364-a4cb-b58a71061f73)
![103](https://github.com/user-attachments/assets/a35056f9-97a2-4aab-9313-8cc6ed83494a)
![105](https://github.com/user-attachments/assets/0c6de1e2-a811-41e5-8671-ca281e189182)
![106](https://github.com/user-attachments/assets/27530dcd-5f66-45b2-82be-9d49d2f71306)
![107](https://github.com/user-attachments/assets/f04d3ee6-7329-4f2b-88cb-5200a80f3619)
![108](https://github.com/user-attachments/assets/4895001a-e0eb-4c9c-abc2-0fb06b99156c)
![109](https://github.com/user-attachments/assets/10a7b714-f057-4f21-8201-101e64c947db)
![110](https://github.com/user-attachments/assets/6fe94251-fb5e-4951-8646-0b07b0f1e320)


### Result:
Thus, a program to check palindrome has been written and test cases have been written and verified successfully.
