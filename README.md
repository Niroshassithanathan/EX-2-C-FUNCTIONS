# EX-2-C-FUNCTIONS
## AIM :
Write a C program to generate Fibonacci Sequence of n numbers using
function without return type 
## ALGORITHAM :
1.Start

2.Declare a function generateFibonacci with the following parameters:
n (number of Fibonacci numbers to generate)
An array to store the Fibonacci sequence

3.Inside the function, declare and initialize the first two Fibonacci numbers (e.g., fib[0] = 0 and fib[1] = 1).

4.Use a loop to generate the Fibonacci sequence from the 3rd element to the nth element:
a. Calculate the next Fibonacci number as the sum of the previous two numbers: fib[i] = fib[i-1] + fib[i-2].

5.End the loop.

6.Print the generated Fibonacci sequence.

7.End.
## PROGRAM :
```
#include <stdio.h>
void fibo(){
int i,n,t1=0,t2=1,a;
scanf("%d",&n);
for(i=1;i<=n;i++) {
printf("%d ",a);
t1=t2;
t2=a;
a=t1+t2;
}
}
int
main(){
fibo();
}
```
## OUTPUT :
![image](https://github.com/Niroshassithanathan/EX-2-C-FUNCTIONS/assets/121418437/b580c160-764d-4e11-b10e-daac25241e97)

## RESULT :
Thus , The C program has been  executed successfully.
