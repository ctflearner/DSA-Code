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
