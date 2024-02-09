# Logical-problems-
#1.
num = int(input("Enter a number: "))
if num > 0:
    print("positive")
elif num < 0:
    print("negative")   
else:
    print("zero")
#2.
age=int(input("Enter a age: "))
if age <= 13:
    print("child")
elif 13 <= age < 18:
    print("teenager")
elif 18 <= age < 65:
    print("adult")
else:
    print("senior")
 #3
num1 = int(input("Enter a number: "))
num2 = int(input("Enter a number: "))

if num1 > num2:
    print("The larger number:", num1)
elif num1 < num2:
    print("The larger number:", num2)
else:
    print("Both are equal")
#4
year= int(input("enter a year: "))
if year % 400 == 0 and (year % 100 != 0 or year % 4 == 0):
    print("leap year")
else:
   ("Not a leap year")
#5.   
grade = int(input("Enter a grade: "))
if 90 <= grade < 100:
    print("A")  
elif 80 <= grade < 90:
    print("B")
elif 70 <= grade < 80:
    print("C")   
elif 60 <= grade < 70:
    print("D")   
elif 50 <= grade < 60:
    print("F")
#6.
# Get user input for three numbers
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))
num3 = float(input("Enter the third number: "))
# Find and print the maximum and minimum
maximum = max(num1, num2, num3)
minimum = min(num1, num2, num3)
#prinr the numbers 
print("Maximum: ", maximum)
print("Minimum: ", minimum)
