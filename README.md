# Balls-and-Boxes
# cook your dish here
for i in range(int(input())):
    n,k = map(int,input().split())
    req = k*(k+1)//2
    if n>=req:
        print('YES')
    else:
        print("NO")
