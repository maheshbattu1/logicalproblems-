# logicalproblems-
# calculate sum of two numbers ??
```
num1=float(input("Enter the 1st number:"))
num2=float(input("Enter the 2nd number:"))
sum=(num1+num2)
print(sum);
```
# output
Enter the 1st number:__
Enter the 2nd number:__
# we assume a any  integers or decimal number  it's output was arrived

# check if a number is even or odd ?
```
num=float(input("Enter a number:"))
if num % 2 ==0:
    print("num is even")
else:
    print("num is odd")
```
# output 
# case 1 we will give input :"101"
Enter a number:101
num is odd
# case 2 we will give input :"100"
Enter a number:100
num is even

# find the largest number ??
```
num1=float(input("Enter 1st number:"))
num2=float(input("Enter 2nd number:"))
num3=float(input("Enter 3rd number:"))
max_num = max(num1, num2, num3)
print(f"The largest number is {max_num}")
              (or)
print("The largest number is ",(max_num))
```
# output
Enter 1st number:25.0
Enter 2nd number:2
The largest number is 46.0 
# note:-Inside an **f-string**, you can include expressions enclosed in curly braces** {} **which will be evaluated at runtime and their results will be inserted into the string.

# check for prime numbers write a simple code in python ?
```
num = int(input("Enter a number: "))
if num > 1:
    for i in range(2, num):
        if (num % i) == 0:
            print(f"{num} is not a prime number.")
            break
    else:
        print((num),"is a prime number.")
else:
    print((num), "is not a prime number.")
```
 # output  
 Enter a number:-7
7 is a prime number 

# Write a Python program that checks if a given year is a leap year ?
```
year = int(input("Enter a year: "))
if (year % 4 == 0 and year % 100 != 0):
    print(year, "is a leap year.")
else:
    print(year, "is not a leap year.")
```
# output
Enter a year:2024
2024 is leap year
Enter a year: 1990
1990 is not a leap year.
# conclusion the above problem<<<<
in the  if condition **(year%4==0)** the condition was satisfied then print t(year, "is a leap year.") 
some other years like eg 1990 is also (year%4==0) satisfied this condition but 1990 is not a leap year....!
then now we can use the Bitwaise operators like **{and ,or , xor, not}**  Here we are choosing operstor is **and** means Sets each if both operators are 1( 1 meams true)
now we implement the **{ year % 100 != 0}** here its not satisfied the condition then the both are not True the 1990 is not a leap year..

#  calculate the area of rectangle ??
```
a = int(input("lenght of side a ="))
b = int(input("breadth of  side b ="))
c = int(input("lenght of  side c ="))
d = int(input("breadth of  side d ="))
s =(((a+c)/2)+((b+d)/2))
print(s)
 ```

 
      



