# Problem-1: Count digits in a number
```javascript
Problem Statement: Given an integer N , write program to count number of digits in N.

#Outout
4
Number of digits in 4 is 1

# Code
def count(n):
    counter = 0 
    x=n
    while(x!=0):
        x=x//10
        counter+=1
    return counter 

taking_input=int(input())
print(f"Number of digits in {taking_input} is {count(taking_input)}")

Time Complexity: O(n) , n is the number of digit in a given integer
Space Complexity: O(1)

```
