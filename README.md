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
Palindrome : exactly equal after reversing 
```python
num = int(input('Enter a number: '))
absNum = abs(num)
rev = absNum % 10
absNum = absNum // 10
while ( absNum > 0):
    r = absNum % 10
    absNum = absNum // 10
    rev = rev*10 + r
if(num < 0):
    rev = rev - 2 *rev 
if(num== rev):
   print('palindrome')
else:
    print('nOT a palindrome')
```

```python
for i in range(10):
   print(i,"Hello world")
```
it will print hello world 10 times 
if (1,10) then it will print from 1 to 9 and if only 10  then 0 to 9 

```python
for i in range(1, 10):
   print(i,"Hello world")
   print("*********")
```
```python
for i in range (10):
    if (i % 2 == 0):
        print(i, "Radhe Radhe")
    else:
        print(i, "Jai Shri Ram")
```
```python
print("enter a number")
n= int(input())

for i in range (1, n+1):
    if (n % 2 == 0):
        print(i, "Radhe Radhe")
    else:
        print(i, "Jai Shri Ram")
```
```python
print("Enter a number:")
n = int(input())

ans = 0 
for i in range(n//2, n):
    ans = ans + i

print ("The sum of all numbers from", n//2, "to", n-1, "is:", ans)
```

Table 
```python
print("enter a number:")
n = int(input())

for i in range(10):
    print(n, "x", i + 1, "=", n * (i + 1))
```
```python
for x in range(1,11):
    if(x % 2 != 0):
        print(x)
```
```python
for x in range(1,11,3):
    print(x)
```
from 1 it will skip  3 and then print 4 and then 7 and then 10
( 1 , 11 , 3) 1 is optional parameter second is mandatory parameter and 3rd is step 
for arcending andd   descending order 

```python
country = 'India'
for letter in country:
    print(letter)
```
range is not used

format printing
```python
d = 10
m = 5
y = 2021
print(f"The date is: {d}/{m}/{y}")
```
```python
d = 10
m = 5
y = 2021
print("The date is:" , d , m, y, sep ='/')
# or we can write
print("The date is:", end = ' ')
print(d, m, y, sep = '/')
```
sep is seperate 
end= ' ' is for writing in single line
```python
num = int(input())
for i in range(1,11):
    print(f'{num} x {i} = {num*i}')
```
f is format printing 
under {] everything will be considered as variable and everything else be considered as string
```python
num = int(input())
for i in range(1,11):
    print('{0} x {1} = {2}'.format(num, i, num*i))
```
```python
num = int(input())
for i in range(1,11):
    print(f'%d x %d = %d' % (num, i, num*i))
```
here f is float value
```python
for x in range(11):
    if(x % 3 == 0):
        print(x)
    else:
        pass
```

<img width="787" height="206" alt="image" src="https://github.com/user-attachments/assets/50e9d5f0-4026-40aa-8542-32ce264ea2b7" />
<img width="835" height="222" alt="image" src="https://github.com/user-attachments/assets/4901c50b-077c-497a-a9c3-304ada1e9fa0" />
<img width="477" height="306" alt="image" src="https://github.com/user-attachments/assets/2001010c-a3bf-4d06-a136-0be4e9efc93d" />


tuple is unchangeable
and list is changeable 
we can appened(Add)
If we want to fix the list then we use tupple

```python
import string 
print(string.ascii_letters)
```
we can't change the specific chahracter in python like we change in digits 
s[3] = 's' it can't be changed 
but s[3] = '3' can be changed 
l.appened can add one element but l.insert can add more than one element 
l.remove(2) removes that element but l.pop() removes the number positioned at that place 
```python
l1 = [2,3,4,5,6,11,1,19,10]
l1.sort(reverse=True)
print(l1)
```
in st(set) only unique value gets printed 
st(1,1,1,1,12,2,23,3,34,4,)

```python
A = {1,2,3}
B = {3,4,5}
print(A.issuperset(B))
```
for union it's A.union(b)
OR A
and for intersection a.difference(B) or A-B
```python
l = [10]
print(l, type(l))

t=(10)
print(t, type(t))
```
[] is for list 
(9,) is tuple and () is just integer 

```python
a=100
b=2
small = a if a< b else b
print(small)
```
```python
a = 5
while a> 0: print(A); a -= 1
```
```python
fruits = ["apple", "banana", "cherry", "date", "elderberry"]

newlist = []
for fruit in fruits:
    if "a" in fruit:
        newlist.append(fruit.capitalize())
    else:
        newlist.append(fruit.capitalize())
print(newlist)
```
```python
fruits = ["apple", "banana", "cherry", "date", "elderberry"]

newlist = []
for fruit in fruits:
    if "a" in fruit:
        newlist.append(fruit.capitalize())
    else:
        "r" in fruit
        newlist.append(fruit.upper())
else:
    print("No fruits found containing 'a' or 'r'")
print(newlist)
```
or we can write
```python
fruits = [....]
newlisr = [fruits.capitalize() for fruit in fruits if 'r' in fruit]
print(newlist)
