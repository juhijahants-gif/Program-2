# Program-2
#Aim
  To write a Python program that checks whether a given number is a palindrome. A palindrome number is a number that remains the same when its digits are reversed.
  
#Algorithm:
step 1:
  Input the number to check
step 2:
  Store the original number in a temporary variable.
step 3:
  Initialize a variable to store the reversed number as 0.
step 4:
  While the number is greater than 0:
step 5:
  Extract the last digit using modulo operation.
step 6:
  Update the reversed number by multiplying the current reversed number by 10 and adding the extracted digit.
step 7:
   Reduce the number by dividing it by 10 (integer division).
step 8:
   Compare the reversed number with the original number.
step 9:
   If both are equal, the number is a palindrome.
   Otherwise, it is not a palindrome.
step 10:
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
