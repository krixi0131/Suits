# Suits
```python

a=int(input())
b=int(input())
c=int(input())
d=int(input())
e=int(input())
f=int(input())
ans=0
for i in range(d+1):
    x=min(a,i)*e
    y=min(b,c,d-i)*f
    ans=max(x+y,ans)
print(ans)
```
