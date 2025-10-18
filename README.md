# Program-2
#Day 1

#Aim:
  
  To write a Python program that checks whether a given number is a palindrome. A palindrome number is a number that remains the same when its digits are reversed.
  
#Algorithm:

#step 1:
  
  Input the number to check
  
#step 2:
  
  Store the original number in a temporary variable.
  
#step 3:
  
  Initialize a variable to store the reversed number as 0.
  
#step 4:
  
  While the number is greater than 0
  
#step 5:
  
  Extract the last digit using modulo operation.
  
#step 6:
  
  Update the reversed number by multiplying the current reversed number by 10 and adding the extracted digit.
  
#step 7:
   
   Reduce the number by dividing it by 10 (integer division).
   
#step 8:
   
   Compare the reversed number with the original number.
   
#step 9:
   
   If both are equal, the number is a palindrome.
   Otherwise, it is not a palindrome.
   
#step 10:
  
   Display the result.
   

#Program:
```
n=int(input())
rev=0
org=n
while n>0:
    rem=n%10
    rev=rev*10+rem
    n//=10
if(rev==org):
  print("The given number",org,"is a Palindrome")
else:
    print("The given number",org,"is not a palindrome")
```

#output:
<img width="998" height="220" alt="Screenshot 2025-10-18 192200" src="https://github.com/user-attachments/assets/6c03a5a0-f1df-44f7-8d4c-6fa32c1662d4" />

#Result:

   The program successfully checks given number as palindrome

#Day 2

#Aim:

   To write a Python program that calculates and displays the sum of the first N natural numbers using a function.

#Algorithm:

#Step 1:

    Take input N from the user, representing how many natural numbers to sum.
    
#Step 2:

   Define a function sum_natural_numbers(n) 
   
#Step 3:

   Initializes a sum variable to 0.
   
#Step 4:

    Uses a loop from 1 to n inclusive to add each number to sum.
    
#Step 5:

   Returns the sum.
   
#Step 6:

   Call the function with the user input N.
   
#Step 7:

    Display the returned sum.

#Program:
```
def sum(n):
    return n*(n+1)//2
n=int(input())
result=sum(n)
print("The sum of first n natural numbers is",result)
```

#output:
<img width="1141" height="264" alt="Screenshot 2025-10-18 195754" src="https://github.com/user-attachments/assets/cb536e80-f202-4d44-8034-dea067d56f39" />

#Result:

  The program successfully finds the sum of natural numbers

#Day 3

#Aim:

   To write a Python function that takes two arguments and returns their sum. The function should be assigned to a variable which can then be used to perform          addition.

#Algorithm:

#Step 1:

   Define a function that accepts two parameters (a, b).
   
#Step 2:

   Within the function, return the sum of the two parameters (a + b).
   
#Step 3:

   Assign this function to a variable named f.
   
#Step 4:

  To use the function, call f with two numbers as arguments.
  
#Step 5:

  Print or return the output of the function call.

#Program:

```
a=int(input())
b=int(input())
f=a+b
print(f)
```
#Output:
<img width="1140" height="254" alt="Screenshot 2025-10-18 200929" src="https://github.com/user-attachments/assets/545f7c65-15d3-45db-bbc6-17ded6403dbe" />

#Result:

  The program successfully calculates sum of natural numbers

#Day 4
#Aim:

   The aim is to write a Python program that prints a pyramid pattern of numbers based on user input for the number of rows.

#Algorithm:
#Step 1:

   Take input from the user for the number of rows (n).
   
#Step 2:

   For each row i from 1 to n
   
#Step 3:

   Print spaces to align the row in pyramid shape (number of spaces = n - i).
   
#Step 4:

   Print numbers from 1 to i with spaces in between.
   
#Step 5:

  Move to the next line after each row is printed.
#Program:
```
num=int(input())
for i in range(1,num+1):
    for j in range(1,i+1):
        print(j,end=" ")
    print()
```
#Output:
<img width="1136" height="501" alt="Screenshot 2025-10-18 201901" src="https://github.com/user-attachments/assets/7570c691-2cac-4e54-95b1-62ed565e70a7" />
#Result:

  The program successfully prints the given pattern
#Aim:

  The aim is to write a Python program that checks whether a given number is even or odd and displays the appropriate message.

#Algorithm:
#Step 1:

   Accept a number as input from the user.
   
#Step 2:

   Use the modulo operator (%) to find the remainder when the number is divided by 2.
   
#Step 3:

  If the remainder is 0, the number is divisible by 2 and hence even.
  
#Step 4:

  Print "<number> is even".
  Else, the number is odd.
  
#Step 5:

  Print "<number> is odd".
#Program:
```
num=int(input())
if num%2==0:
    print(num,"is even")
else:
    print(num,"is odd")
```
#Output:
<img width="933" height="189" alt="Screenshot 2025-10-18 202817" src="https://github.com/user-attachments/assets/8ac477a1-1fcd-437c-986e-14425a6edda3" />
#Result:

  The program successfully checks the given number as even or odd






   
