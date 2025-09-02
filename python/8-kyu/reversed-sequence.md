# Reversed sequence

## Instructions
Build a function that returns an array of integers from n to 1 where n > 0.

### Example
```
n = 5 --> [5, 4, 3, 2, 1]
```

## Solution

```python
def reverse_seq(n):
    sequence = []
    
    for i in range(n, 0, -1):
        sequence.append(i)
        
    return sequence
```
