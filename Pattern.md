# PATTERN

# PATTERN-1
```python
******
******
******
******
******
******


# CODE

taking_input = int(input())

for i in range(taking_input):
    print('*' * taking_input)
```

# PATTERN-2

```python
*
**
***
****
*****

# CODE

taking_input = int(input())

for i in range(0, taking_input+1):
    print('*' * i)
```

# PATTERN-3

```python
1
12
123
1234
12345
123456

#code

taking_input = int(input())

for i in range(1, taking_input+1):
    for j in range(1, i+1):
        print(j, end="" )
    print()
```

# PATTERN-4

```python
1
22
333
4444
55555

# Code
taking_input = int(input())

for i in range(1, taking_input+1):
    for j in range(1, i+1):
        print(i, end="" )
    print()
```

# PATTERN-5

```python
*****
****
***
**
*

#Code

taking_input = int(input())

for i in range(1, taking_input+1):
    print('*' * taking_input)
    taking_input-=1
   
```
