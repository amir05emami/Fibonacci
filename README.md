# Fibonacci
f1 = 0
f2 = 1

x1 = int(input("Enter number 1 : "))
x2 = int(input("Enter number 2 : "))

while f2 < x2:
    if f2 >= x1:
        print(f2)
    f3 = f1 + f2
    f1 = f2
    f2 = f3
