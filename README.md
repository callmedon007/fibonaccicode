# fibonaccicode
n= int(input("enter a limit:"))
(x,y)=(0,1)
if n<=0 :
    print("enter a positive limit.")
elif n==1:
    print("the fibonacci series upto", n, "is:")
    print(x)
else:
    print("the fibonacci series:")
    for i in range(0,n):
        print(x,end=" ")
        c=x+y
        x=y
        y=c
