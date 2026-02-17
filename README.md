# Factorial-of-a-number-using-recursion
def fact(n):
    if n == 1 or n == 0:
        f = 1
    else:
        f = n * fact(n - 1)
    return f
num = int(input("Enter an integer: "))
result = fact(num)
print("The factorial of", num, "is:", result)

OUTPUT:
Enter an integer: 5
The factorial of 5 is: 120
