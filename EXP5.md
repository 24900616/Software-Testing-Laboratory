### Ex.No:5 Binary Search
### Date:27.3.25
### Register Number: 212224230284

### AIM: 
Write a python program for Binary Search and inspect for failures.

### Algorithm:

1.Start the program.

2.Get the list from the user

3.Get the element to be searched

4.Compare the mid element with the key, if same return the index

5.If key is greater, search it in the right side, else search it in the left side.

6.If not found return -1

7.Stop the program..


### Program:
```
def binary_search(arr, x): 
    low = 0 
    high = len(arr) - 1 
    mid = 0 
    while low <= high: 
        mid = (high + low) // 2 
        if arr[mid] < x: 
            low = mid + 1 
        elif arr[mid] > x: 
            high = mid - 1 
        else: 
            return mid
arr = [2, 3, 4, 10, 40] 
x = input("Enter the element to be searched: ")
try: 
    x = int(x) 
    result = binary_search(arr, x) 
    if result != -1: 
        print("Element is present at index", str(result)) 
    else: 
        print("Element is not present in array") 
except: 
    print("Enter a valid input!")
```

### Output:

 ![stl40](https://github.com/user-attachments/assets/0abb737a-fb50-41cc-80eb-1289bbce570b)
 ![stl41](https://github.com/user-attachments/assets/7a891bce-119a-4f65-a260-e763f0d7ea1a)
 ![stl43](https://github.com/user-attachments/assets/62f764db-5922-46ef-90a0-87edf92197a4)
 ![stl44](https://github.com/user-attachments/assets/96ac36f6-762f-4127-8dae-cdff710cdf0f)
 ![stl45](https://github.com/user-attachments/assets/eaee37f1-4def-4329-a6cc-82bbf7bb86c3)
 ![stl46](https://github.com/user-attachments/assets/bc7957fe-a70e-4426-81a1-64654817f0cd)
 ![stl47](https://github.com/user-attachments/assets/63628c98-43f7-4b95-a706-a7b45a99e402)
 ![stl48](https://github.com/user-attachments/assets/b4266341-861c-4473-8f0b-de515ebe0c23)
 ![stl49](https://github.com/user-attachments/assets/c6345952-3c08-42c3-b49c-66dd67f85453)
 ![stl50](https://github.com/user-attachments/assets/675d1ec4-bc3b-4483-b9ef-20de61ebfa8b)


### Result:
Thus, the python program for Binary Search implemented and the output is verified successfully.

