# ass-3-3-7-22
Assignment-3
n=int(input())
l=list(map(int,input().split()))
for i in l:
    if i%2==0:
        l.remove(i)
print(l)
