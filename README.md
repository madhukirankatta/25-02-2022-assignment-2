# 25-02-2022-assignment-2
n=int(input('enter value: '))
l=[]
t=[]
for i in range(n):
    x=int(input())
    l.append(x)
for i in range(n):
    if l[i]==0:
        continue
    else:
        t.append(l[i])
print("non-zero values: ",t,"count of non zero: ",len(t))
