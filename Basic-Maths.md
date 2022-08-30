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

# Problem-2: Reverse a number 

```javascript

Problem Statement: Given a number N reverse the number and print it.
123456
Reverse of a  number : 654321

# Code
def reverse_a_number(taking_input):
    return str(taking_input)[::-1]
    
taking_input = int(input())
print(f"Reverse of a  number : {reverse_a_number(taking_input)}")
```

# Problem-3:Check if a number is Palindrome or Not 
```javascript
Problem Statement:  Given a number check if it is a palindrome.

# Output:
123
Not a Palindrome Number




#-Code
def check_palindrome(taking_input):
    copy_of_the_number=taking_input
    converting=int(str(copy_of_the_number)[::-1])
    if converting == taking_input:
        print("Palindrome Numer")
    else:
        print("Not a Palindrome Number")


taking_input = int(input())
check_palindrome(taking_input)
```

# Problem-3:Find GCD of two numbers
```javascript
Problem Statement: Find gcd of two numbers.

# Output:
4
8
The gcd of two number is: 4

#code
def hcf(a,b):
    if b==0:
        return a 
    else:
        return hcf(b,a%b)
    
taking_first_number=int(input())
taking_Second_number=int(input())

print(f"The gcd of two number is: {hcf(taking_first_number,taking_Second_number)}")
```

# Problem-4: Check if a number is Armstrong Number or not
```javascript
Problem Statement: Given a number, check if it is Armstrong Number or Not.

# Output:
153
Yes, it is Armstrong Number

# CODE
def checking_armstrong(taking_input):
    copying_the_number = taking_input
    sum_of_the_number =0
    while(copying_the_number!=0):
        remainder = copying_the_number % 10
        sum_of_the_number+=remainder**3
        copying_the_number = copying_the_number//10
    if taking_input == sum_of_the_number:
        print("Yes, it is Armstrong Number")
    else:
        print("No it is not a Armstrong Number")
    

taking_input = int(input())
checking_armstrong(taking_input)


```

# Problem-5: Print all Divisors of a given Number
```javascript
Given a number, print all the divisors of the number. A divisor is a number that gives remainder as zero when divided.

#Output:
36
1 2 3 4 6 9 12 18 36

# Code
def checking_for_divisor(taking_input):
    for i in range(1,taking_input+1):
        if (taking_input%i==0):
            print(i, end=" ")
    print()        
            

taking_input = int(input())
checking_for_divisor(taking_input)
```

# Problem-6:
```javascript


Problem statement: check whether a number is prime or not

#Code
def check_prime(taking_input):
    if taking_input > 1:
        for i in range(2, int(taking_input/2)+1):
            if(taking_input%i==0):
                print(f"{taking_input},is not a prime number")
                break
            else:
                print(f"{taking_input},is a prime number")
                break
    
    else:
        print(f"{taking_input},is not a prime number")
        
        
        
taking_input=int(input()) 
check_prime(taking_input)
        
```
