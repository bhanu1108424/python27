# python27
rombus pattern
n=int(input("enter the size"))
for i in range(1,n+1):
    for j in range(n-i):
        print(' ',end=' ')
    for k in range(2*i-1):
        print("*",end=' ')
    print()
for i in range(n,0,-1):
    for j in range(n-i):
        print(' ',end=' ')
    for k in range(2*i-1):
        print("*",end=' ')
    print()
