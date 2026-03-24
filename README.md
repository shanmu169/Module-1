# NAME: Shanmuga Priya .K
# REGISTER NO: 25004352

# EXP NO: 1a) C PROGRAM TO FIND THE ASCII VALUE OF THE GIVEN CHARACTER.
# AIM:
To write a C program to find the ASCII value of the given character.

# ALGORITHM:
1. Take the given character from the user as input using scanf function.
2. Convert the character into the ASCII value using %d.
3. Print the value using printf.

# PROGRAM:
```
#include<stdio.h>
int main()
{
    char ch1;
    scanf("%c",&ch1);
    printf("ASCII value of %c is %d",ch1,ch1);
    return 0;
}
```
# OUTPUT:
![alt text](<Screenshot 2025-10-18 223259.png>)

# RESULT:
Thus, the program is verified successfully.

# EXP NO: 1b) C PROGRAM TO READ N VALUE AND TO CHECK WHETHER THE VALUE IS EQUAL TO 10 OR NOT USING IF-ELSE.
# AIM:
To write a C program to read N value and to check whether the value is equal to 10 or not using if-else.

# ALGORITHM:
1. Take the given number from the user as input using scanf function.
2. Using if condition, check if the given number is equal to 10 or not.
3. If it is 10, print the given statement using printf.
4. If not, the else block will be executed.

# PROGRAM:
```
#include<stdio.h>
int main()
{
    int num;
    scanf("%d",&num);
    if(num==10)
      printf("Given number is TEN.");
    else
      printf("Given number is NOT TEN.");
    return 0;
}
```
# OUTPUT:
![alt text](<Screenshot 2025-10-20 112947.png>)

# RESULT:
Thus, the program is verified successfully.

# EXP NO: 1c) C PROGRAM TO CHECK WHETHER THE GIVEN NUMBER IS EVEN OR NOT USING CONDITIONAL OPERATORS.
# AIM:
To write a C program to check whether the given character is even or not using conditional operators.

# ALGORITHM:
1. Take the given number from the user as input using scanf function.
2. Using if condition and %2, check if the given number is even  or not.
3. If it is even , print the given statement using printf.
4. If not, the else block will be executed.

# PROGRAM:
```
#include <stdio.h>
#include<math.h>
int main()
{
    int num;
    scanf("%d",&num);
    if((num%2)==0) printf("The number is Even");
    else printf("The number is not Even Number");
    return 0;
}
```
# OUTPUT:
![alt text](<Screenshot 2025-10-20 113510.png>)

# RESULT:
Thus, the program is verified successfully.

# EXP NO: 1d) C PROGRAM TO SIMULATE ARITHEMETIC OPERATORS(+,-) USING SWITCH STATEMENT.
# AIM:
To write a C program to simulate arithmetic operators using switch statement.

# ALGORITHM:
1. Take the given numbers and character from the user as inputs using scanf function.
2. Using switch condition, check the type of arithmetic operations(cases).
3. Print according to the cases using printf.
4. If no case is true, then the default case will be executed.

# PROGRAM:
```
#include<stdio.h>
int main()
{
    int num1,num2,result;
    char op;
    scanf("%d %c %d",&num1,&op,&num2);
    switch(op)
    {
        case '+':
          result=num1+num2;
          printf("Result = %d\n",result);
          break;
        case '-':
          result=num1-num2;
          printf("Result = %d\n",result);
          break;
        default:
          printf("Invalid Input\n");
    }
    return 0;
}
```
# OUTPUT:
![alt text](<Screenshot 2025-10-20 114122.png>)

# RESULT:
Thus, the program is verified successfully.

# EXP NO: 1e) C PROGRAM TO READ A NUMBER AND CHECK WHETHER THE NUMBER IS DIVISIBLE BY 6 OR NOT USING IF-ELSE.
To write a C program to read a number and check whether the number is divisible by 6 or not using if-else.

# ALGORITHM:
1. Take the given number from the user as input using scanf function.
2. Using if condition, check whether the number is divisible by 6 or not.
3. If it is true, print the statement using printf function.
4. If not, then the else block will be executed.

# PROGRAM:
```
#include<stdio.h>
int main()
{
    int num;
    scanf("%d",&num);
    if((num%6)==0) printf("Divisible by 6");
    else printf("Not Divisible by 6");
    return 0;
}
```
# OUTPUT:
![alt text](<Screenshot 2025-10-20 114751.png>)

# RESULT:
Thus, the program is verified successfully.








