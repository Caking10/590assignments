# Weekly Task 2 
![huh](https://media.giphy.com/media/RLUyfJnogtXK44pm9t/giphy.gif?cid=ecf05e47n1wqag34fii52sbyus99aoucjf8sfl1e5uftwp2k&rid=giphy.gif&ct=g)

Remember the rules of ~Fight~ Code Club:
1. ALWAYS DOCUMENT
2. Cite resources that you use (paste links)
3. Include the names people who you worked with
4. Be neat and organized

### 1. Create a list of 10 countries. 

### Assign that to a variable.


```python
#A simple list of ten countries as strings
ListOfCountries = ['France', 'China', 'United States', 'United Kingdom', 'Egypt', 'South Korea', 'North Korea', 'Japan', 'Botswana', 'Germany']
```

### 2. Create a dictionary that maps those 10 countries to their capitols. make the keys are the country and the values are the capitols.

### Assign that to a different variable.


```python
#Simple dictionary with countries (keys) and their capitals (values), both as strings
DictionaryOfCountries = {'France':'Paris', 'China':'Beijing', 'United States':'Washington D.C.', 'United Kingdom':'London', 'Egypt':'Cairo', 'South Korea':'Seoul', 'North Korea':'Pyongyang', 'Japan':'Tokyo', 'Botswana':'Gaborone', 'Germany':'Berlin'}
```

### 3. Add another country to the dictionary you created in question 2


```python
#Adding Spain as a key and Madrid as a value, both as strings
DictionaryOfCountries['Spain'] = 'Madrid'
```

### 4. Slice your country *list* so that it reveals items in position 3 through 8.


```python
#Slicing the list, ending at 9 as to reveal the 8th position.
ListOfCountries[3:9]
```

### 5.
### A. Create a second country list (that is not identical to the one in Q4).
### B. Use the appropriate operator to find the common elements between the list in Q4 and Q5A.


```python
#Was kind of lost here, couldn't come up with anything other than a boolean operation.
import numpy as np
ListOfCountries = ['France', 'China', 'United States', 'United Kingdom', 'Egypt', 'South Korea', 'North Korea', 'Japan', 'Botswana', 'Germany']
ListOfCountries2 = ['China', 'Egypt', 'Myanmar', 'Cambodia', 'Ghana', 'Jamaica', 'Canada', 'Germany', 'Bahrain', 'Nepal']

def func(a,b)
    a = ListOfCountries
    b = ListOfCountries2
    if a == b:
        print("These are the same")
    else:
        print("Not the same")
```
