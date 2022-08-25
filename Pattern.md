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
# PATTERN-6

```python

1 2 3 4 5 
1 2 3 4 
1 2 3 
1 2 
1 


#code
taking_input = int(input())

for i in range(taking_input+1, 1, -1):
    for j in range(1,i):
        print(j, end=" ")
    print()
```

# PATTERN-7
```python
*
**
***
****
*****
****
***
**
*

# code
taking_input = int(input())

for i in range(1,taking_input+1):
    print('*'*i)
if(i==taking_input):
    for j in range(taking_input-1,0,-1):
        print('*'*j)

```

# PATTERN-8
```python
1 
0 1 
1 0 1 
0 1 0 1 
1 0 1 0 1

# Code
taking_input = int(input())

for i in range(1,taking_input+1):
    for j in range(i,i+i):
        print(j%2, end=" ")
    print()   
```

# PATTERN-9
```python






# code
taking_input = int(input())

#for i in range(1,taking_input+1):
 #   for j in range(1,i+1):
  #      print(j, end="")
   # print()
for i in range(taking_input,1,-1):
    for j in range(i+1,1,-1):
        print(j, end="")
    print()    
```

# PATTERN-10
```python
1      1
12    21
123  321
12344321


# Code
taking_input=int(input())

for i in range(1,taking_input+1):
    for j in range(1,taking_input+1):
        if(j<=i):
            print(j, end="")
        else:
            print(" ", end="")
    for k in range(taking_input,0,-1):
        if(k<=i):
            print(k, end="")
        else:
            print(" ", end="")
    print() 
```
