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
