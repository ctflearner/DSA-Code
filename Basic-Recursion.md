# Problem-1: printing names N times
```javascript
def printing_name(i,taking_input):
    if(i>taking_input):
        return
    else:
        print("yourname")
        printing_name(i+1,taking_input)
        
taking_input = int(input())       
printing_name(1,taking_input) 
```
# Problem-2: Print 1 to N using recursion

```javascript
def printing_number(i,taking_input):
    if(i>taking_input):
        return
    else:
        print(i)
        printing_number(i+1,taking_input)
    
taking_input=int(input())
printing_number(1,taking_input)
```
# Problem-3: Print N to 1 using Recursion
```javascript
def printing_number(taking_input,i):
    if(taking_input==0):
        return
    else:
        print(taking_input)
        printing_number(taking_input-1,i)
    
taking_input=int(input())
printing_number(taking_input,1)
```

# Problem-4: Sum of the first N number
```javascript
PARAMETER-RECURSION
========================
def sum_of_number(taking_input,sum_of_the_number):
    
    if(taking_input<1):
        print("Sum of the number:",sum_of_the_number)
        return
    else:
        sum_of_number(taking_input-1, sum_of_the_number+taking_input)
        


taking_input = int(input())
sum_of_number(taking_input,0)


===================
FUNCTIONAL-RECURSION
====================

```
