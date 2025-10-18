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


   
