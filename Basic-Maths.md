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
--------------------------------------------------------------------------------------------

# Code-2

def count_digit(taking_input):
    converting_to_string = str(taking_input)
    return len(converting_to_string)
    

taking_input = int(input())
print(f"Number of digits in {taking_input} is {count_digit(taking_input)}")

Time Complexity: O(1)
Space Complexity: O(1)


```
