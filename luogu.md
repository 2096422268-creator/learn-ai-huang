#Problem 1  
```python
a=input()
b=input()
print(int(a)+int(b))
```
#Problem 2
```python
apple=list(map(int,input().split()))
height=int(input())
height+=30
count=0
for i in apple:
    if i<=height:
        count+=1
print(count)
```
#Problem 3
```python
x,y=map(int,input().split())
leap_years=[]
for year in range(x,y+1):
    if (year%4==0 and year%100!=0) or (year%400==0):
        leap_years.append(year)
print(len(leap_years))
print(*leap_years)
```
#Problem 4
```python
import math
n=int(input())
def isprime(n):
    if n<2 or n%2==0:
        return False
    if n==2:
        return True
    for i in range(3,int(math.isqrt(n))+1,2):
        if n%i==0:
           return False
    return Ture
if isprime(n):
    print("YES")
else:
    print("NO")
```
