# week3

```python
print("When did India get its independence?")
year =int(input())

if(year == 1947):
    print("Correct answer")
else:
    print("Opps, wrong answer.")
    print("THAT'S okay, I will give you a hint, India got its independence in the 20th century.")
    print("when did India get its independence?")
    year = int(input())
    if(year == 1947):
        print("Correct answer")
    else:
        print("you're dumb, the answer is 1947. India got its independence in 1947.")
```

```python
print("When did India get its independence?")
year =int(input())
while(year!=1947)
     print("You got this wrong. Enter again")
     year=int(input())
print("Wow you got it right)
```
this is while loop where we answer until it gets correct
while<condition>
    write whatever you want here 
    write watever you want 
    .....

Factorial!!!!

```python
print("enter a number")
n=int(input())
answer =1
answer = answer*2
answer = answer*3
answer = answer *3
answer = answer * 4
aswer = answer*5

print(Answer)
```

```python
print("Enter a number")
n= int(input())
i=1
answer = 1
while (i<=n):
      answer = answer*1
      i=i+1
print(Answer)
```
i=1
answer =1 
n=5
answer =1
i=2
answer=2
i=3
answer = 6
i=4
answer = 24
i=5
answer =120
i=6
factorial
```python
num = int(input('Enter a number: '))
fact = 1
if (num < 0 ):
   print('Not defined')
else
while (num>0) :
   fact = fact*num num = num-1 
print(fact)
```
```python
num = abs(int(input('Enter a number: ')))
#absolute value
digits = 1
while(num >9):
    num = num // 10
    digits = digits + 1
print(digits)
```
```python
num = int(input('enter a number : '))
absNum = abs(num)
rev = num % 10
num = num//10
while ( num > 0):
    r = num % 10
    num = num // 10
    rev = rev*10 + r
print(rev)
```
```python
num = int(input('Enter a number: '))
absNum = abs(num)
rev = absNum % 10
absNum = absNum // 10
while ( absNum > 0):
    r = absNum % 10
    absNum = absNum // 10
    rev = rev*10 + r
if(num>= 0):
   print(rev)
else:
    print(rev - 2* rev)
print(rev)
```
