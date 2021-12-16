```python
fruits=["apple","banana","mango"]
for x in fruits:
    print(x)
```

    apple
    banana
    mango
    


```python
for number in range(10):
    print("thank you")
```

    thank you
    thank you
    thank you
    thank you
    thank you
    thank you
    thank you
    thank you
    thank you
    thank you
    


```python
for x in "apple":
    print(x)
```

    a
    p
    p
    l
    e
    


```python
languages = ['R', 'Python',  'Scala', 'Java', 'Julia']

for index in range(len(languages)):
   print('Current language:', languages[index])
```

    Current language: R
    Current language: Python
    Current language: Scala
    Current language: Java
    Current language: Julia
    


```python
number = 2  

while number < 5 :  
    print("Thank you")
    number = number+1
```

    Thank you
    Thank you
    Thank you
    


```python
number=1
while number < 5 :  
  
    if number%2 == 0:  
        print("The number "+str(number)+" is even")
    else:
        print("The number "+str(number)+" is odd")

   
    number = number+1
```

    The number 1 is odd
    The number 2 is even
    The number 3 is odd
    The number 4 is even
    


```python
marks = 60
if marks >= 90:
  grade = 'A'
elif marks >= 80:
  grade = 'B'
elif marks >= 70:
  grade = 'C'
elif marks >= 60:
  grade = 'D'
else:
  grade = 'F'
print(grade)
```

    D
    


```python
weeks=['Sunday','Monday','Tuesday','Wednesday','Thursday','Friday','Saturday']

for x in weeks:
    if x=='Sunday':
     continue
    if x=='Monday':
     continue
    if x=='Tuesday':
     continue
    if x=='Saturday':
     continue
    print(x)
```

    Wednesday
    Thursday
    Friday
    


```python
weeks=['Monday','Tuesday','Wednesday','Thursday','Friday','Saturday','Sunday']

for x in weeks:
    if x=='Sunday':
     print('No AI and ML class in Sunday')
     continue
    if x=='Monday':
     print('No AI and ML class in Monday')   
     continue
    if x=='Tuesday':
     print('No AI and ML class in Tuesday')   
     continue
    if x=='Saturday':
     print('No AI and ML class in Saturday')   
     continue
    print(x)
```

    No AI and ML class in Monday
    No AI and ML class in Tuesday
    Wednesday
    Thursday
    Friday
    No AI and ML class in Saturday
    No AI and ML class in Sunday
    


```python

```
