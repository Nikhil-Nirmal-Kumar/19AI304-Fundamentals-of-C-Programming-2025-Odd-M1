# 19AI304-Fundamentals-of-C-Programming-2025-Odd-M1
# IAPR-1- Module 1 - FoC
## 1. Implementation of basic C programs using Literals,Consonants, Variables, Data types.
## 2. Implementation of different categories of operators.
# Ex.No:1
  Build a C program to demonstrate the usage of different types of literals: integer, float, character, and string.  
# Date : 
# Aim:
To build a C program that prints integer, float,character, and string literals on the console using the printf() function.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Inside the main() function, use printf() to display each literal along with its size in bytes using sizeof() :
  
   3.1 Integer literal (e.g., 10) using `%d`
   
   3.2 Float literal (e.g., 3.14) using `%f`
   
   3.3 Character literal (e.g., 'A') using `%c`
   
   3.4 String literal (e.g., "Hello C") using `%s`
   
### Step 4: 
   Stop
# Program:
```
#include <stdio.h>
int main(){
    int intLiteral=25;
    float floatLiteral=25.5;
    char charLiteral='c';
    char stringLiteral[]="Twenty Five";
    printf("Integer Literal = %d\n",intLiteral);
    printf("Float Literal = %f\n",floatLiteral);
    printf("Char Literal = %c\n",charLiteral);
    printf("String Literal = %s",stringLiteral);
}
```
# Output:
<img width="360" height="115" alt="image" src="https://github.com/user-attachments/assets/b9d86acc-586b-4745-8e46-399bc7bcf6cf" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:2
  Build a C program to display the value of a macro constant and a constant variable.
# Date : 
# Aim:
  To build a C program that demonstrates the use of macro constants and constant variables.
# Algorithm:
### Step 1:
  Start  
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Define a macro constant `PI` with value `3.14159` using `#define`.
### Step 4: 
   Inside `main()`:
   
   4.1 Declare a constant integer variable `DAYS`
   
   4.2 Initialize it with the value `7`
   
### Step 5:  
  Use `printf()` to display the values of `PI` and `DAYS`.     
### Step 6:  
  Stop
# Program:
```
#include <stdio.h>
#define pi 3.14159
int main(){
    const int max=100;
    printf("Macro constant (pi) = %f\n",pi);
    printf("Constant Variable (max) = %d",max);
}
```
# Output:
<img width="366" height="70" alt="image" src="https://github.com/user-attachments/assets/4798501f-79b6-4957-8647-e37470761f77" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:3
  Build a C program to demonstrate the use of different data types such as int, float, double, and char, and display their values using printf().
# Date : 
# Aim:
  To build a C program that declares variables of various data types—integer, float, double, and character—initializes them, and prints their values on the screen.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Inside main(), declare and initialize variables of types int, float, double, and char.
### Step 4: 
   Display their values using printf().
### Step 5:    
   Stop
# Program:
```
#include <stdio.h>
int main(){
    int a=45;
    float b=45.5;
    double c=123.456;
    char d='A';
    printf("Integer = %d\n",a);
    printf("Float = %.2f\n",b);
    printf("Double = %.2f\n",c);
    printf("Character = %c\n",d);
    return 0;
}
```
# Output:
<img width="215" height="134" alt="image" src="https://github.com/user-attachments/assets/e1551fa3-6db7-4dc2-98f1-1c60ca2e4d0f" />

# Result: 

# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:4
  Build a C program to perform arithmetic and bitwise operations on two integers entered by the user. The program should display: Arithmetic operations: addition, subtraction, multiplication, division, and remainder. Bitwise operations: AND, OR, XOR, left shift, right shift, and NOT.
# Date : 
# Aim:
  To build a C program that takes two integers as input and demonstrates the arithmetic and bitwise operations, displaying the results of each operation.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Declare two integer variables a and b.
### Step 4: 
   Prompt the user to enter two integers and read the input using scanf().
### Step 5:    
   Perform arithmetic operations on a and b:
   #### Sum (a + b)
   #### Difference (a - b)
   #### Product (a * b)
   #### Quotient (a / b)
   #### Remainder (a % b)
### Step 6: 
  Perform bitwise operations on a and b:
  #### AND (a &amp; b)
  #### OR (a | b)
  #### XOR (a ^ b)
  #### Left shift (a << b)
  #### Right shift (a >> b)
  #### Bitwise NOT of a (~a) and b (~b)
### Step 7:   
  Display the results of all operations using printf().
### Step 8:   
  Stop
# Program:
```
#include <stdio.h>
int main(){
    int a,b;
    printf("Enter Integer 1 : \n");
    scanf("%d",&a);
    printf("Enter Integer 2 : \n");
    scanf("%d",&b);
    printf("Arithmetic Operations on a and b are:\n");
    printf("Sum (a+b) = %d\n",a+b);
    printf("Difference (a-b) = %d\n",a-b);
    printf("Product (a*b) = %d\n",a*b);
    printf("Quotient (a/b) = %d\n",a/b);
    printf("Remainder (a%b) = %d\n",a%b);
    printf("\n");
    printf("Bitwise Operations on a and b are:\n");
    printf("AND (a&b) = %d\n",a&b);
    printf("OR (a|b) = %d\n",a|b);
    printf("XOR (a^b) = %d\n",a^b);
    printf("Left Shift (a<<1) = %d\n",a<<1);
    printf("Right Shift (a>>1) = %d\n",a>>1);
    printf("Bitwise NOT of a = %d\n",~a);
    printf("Bitwise NOT of b = %d\n",~b);
}
```
# Output:
<img width="476" height="593" alt="image" src="https://github.com/user-attachments/assets/ab85665f-1b8a-4799-8622-63c3588d1bfb" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:5
  Develop a C program to check whether a given character is a vowel, consonant, digit, or special symbol using the ternary operator.
# Date : 
# Aim:
  To develop and implement a C program that classifies a character as a vowel, consonant, digit, or special symbol using the ternary operator.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Input a character ch from the user.
### Step 4: 
   Check if ch is a digit ('0' to '9').
   
   If true → Print "Digit" → Go to Step 8.
   
   If false → Go to Step 5.
   
### Step 5:    
   Check if ch is an alphabet letter ('A' - 'Z' or 'a' – 'z').
   
   If true → Go to Step 6.
   
   If false → Go to Step 7.
   
### Step 6: 
   Check if ch is a vowel (a, e, i, o, u or A, E, I, O, U).
   
   If true → Print "Vowel" → Go to Step 8.
   
   If false → Print "Consonant" → Go to Step 8.
   
### Step 7:   
   Print "Special Symbol".
### Step 8:   
  Stop
# Program:
```
#include <stdio.h>
int main(){
    char a;
    printf("Enter a character of your choice:\n");
    scanf("%c",&a);
    if ((a>='a')&&(a<='z')||(a>='A')&&(a<='Z')){
        if ((a=='A')||(a=='E')||(a=='I')||(a=='O')||(a=='U')||(a=='a')||(a=='e')||(a=='i')||(a=='o')||(a=='u')){
            printf("Vowel.");
        }
        else{
            printf("Consonant");
        }
    }
    else if ((a>='0')&&(a<='9')){
        printf("Digit.");
    }
    else{
        printf("Special Symbol.");
    }
}
```
# Output:
<img width="422" height="87" alt="image" src="https://github.com/user-attachments/assets/6d965674-7c56-4b6a-9dd5-5a03c1d28481" />
<img width="454" height="86" alt="image" src="https://github.com/user-attachments/assets/33da2874-1073-4607-8842-359184006a0c" />
<img width="430" height="106" alt="image" src="https://github.com/user-attachments/assets/8fe060d9-0c79-4b31-b7b0-d1e2df1b7fbd" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


