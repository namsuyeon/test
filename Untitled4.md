```python
from tkinter import *
alp={}
infile=open("C:\\HumptyDumpty.txt","r")
rfile=infile.read()
infile.close()

for line in rfile:
    for ch in line:
        if ch in alp:
            alp[ch]+=1
        else:
            alp[ch]=1
print(alp)
```

    {'H': 3, 'u': 7, 'm': 6, 'p': 6, 't': 13, 'y': 5, ' ': 22, 'D': 2, 's': 5, 'a': 11, 'o': 4, 'n': 7, 'w': 1, 'l': 9, ',': 1, '\n': 3, 'h': 5, 'd': 3, 'g': 5, 'r': 3, 'e': 7, 'f': 1, '.': 2, 'A': 1, 'k': 2, 'i': 3, "'": 3, 'C': 1}
    


```python

```
