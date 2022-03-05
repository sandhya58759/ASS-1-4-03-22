# ASS-1-4-03-22
PROGRAM TO COUNT THE DUPLICATE ELEMENTS IN LIST
l=[]
n=int(input())
for i in range(n):
    x=int(input())
    l.append(x)
print(l)
res=[]
for i in l:
    if l.count(i)>1: 
        if i not in res:
          res.append(i)
print(i)
OUTPUT:
1
