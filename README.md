## EX 3 C program to find number of years based on principle,rate & simple interest.
## AIM:
To write a C program to find number of years based on principle,rate & simple interest.

## Algorithm
1.Start.
2.Declare the variables.
3.Prompt the user to enter a value.
4.Read the value using scanf.
5.Calculate the number of years using the formula:
6.End .
## Program:
#include <stdio.h> 
#include <math.h>
int main()
{ float p,n,r,si,ci; 
scanf("%f%f%f", &p,&n,&r);
si=((pnr)/100);
ci=(p)*(pow((1+ r/100),n));
printf("Simple Interest = %0.2f\nCompound Interest = %0.2f", si,ci);
return 0; }

Output:
![image](https://github.com/user-attachments/assets/1b5e4f1f-ff20-43da-9ae8-a387c956970c)


Result:
Thus the program was executed and the output was verified successfully.
