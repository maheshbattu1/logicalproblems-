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
num=int(input("Enter a number:-"))
if num>1:
    for i in range (2,0,num):
        print(num,"is not a prime number")
        break
    else:
          print(num,"is a prime number")
```

 # output  
 Enter a number:-7
7 is a prime number 
  but i can't do this problem 100% solution because if I Enter an another number:-23
23 is not a prime number 
      



