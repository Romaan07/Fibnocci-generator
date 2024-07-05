#Fibnnaci generator
#count is the number of fibnnaci number ......
def fibonacci(count):
    first=0
    second=1
    print(first)
    print(second)
    for i in range(0,count-2):
        third=first+second
        print(third)
        first=second

title="welcome to fibonacci Generator"
title.center(83)
count=int(input("enter the numberof Fibonacci to show "))
fibonacci(count)
print('\n\n THANK YOU')
    
