Assignment no.03 
Que.6 Write program to display 
    - data types , memory address and size in bytes in a variable entered by a user.
```python
x = input("Enter any value: ")

print("Data type:", type(x))

print("Memory address:", id(x))

import sys
print("Size in bytes:", sys.getsizeof(x))
```

OUTPUT - 

<img width="698" height="177" alt="Screenshot 2026-06-22 150213" src="https://github.com/user-attachments/assets/a664cc0c-5dd1-48b1-b81d-bc84fa9784c2" />
