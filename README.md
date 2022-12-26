# factorial
num=int(input("enter the integer number:"))

if num<0:
    print("no factorialfor negative number")
else:
    factorial=1
    n=2
    while n<= num:
          factorial= factorial *n
          n = n+1
    print("factorial of",num,"is",factorial)
    

