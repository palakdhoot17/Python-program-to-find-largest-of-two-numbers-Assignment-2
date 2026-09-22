# Python-program-to-find-largest-of-two-numbers-Assignment-2
# Program to find the largest of three numbers

a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))

if a >= b and a >= c:
    print("Largest number is:", a)
elif b >= a and b >= c:
    print("Largest number is:", b)
else:
    print("Largest number is:", c)

#      OUTPUT
# Enter first number: 5
# Enter second number: 10
# Enter third number: 3
# Largest number is: 10
     
