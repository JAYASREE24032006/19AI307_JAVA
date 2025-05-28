# EX.NO:1(B) VARIABLES AND OPERATOR

## AIM:
To write a Java program to swap the values of the two variables by without using a third variable. After swapping the values should be PRINT.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Define a class named 'Demo'
4.	Implement the main method
5.	Create a new instance of the 'Scanner' class named 'sc' to read user input
6.	Read an integer 'a' from the user using the 'nextInt' method of 'sc'
7.	Read another integer 'b' from the user using the 'nextInt' method of 'sc'
8.	swap the variables and a and b using arithmetic operations.
9.	End





## PROGRAM:
 ```
/*
Program to implement a variable and operators using Java
Developed by: Jayasree R
RegisterNumber:  212223040074
*/
```

```
import java.util.Scanner;
public class Demo
{
    public static void main(String[] args) 
    {
        Scanner scanner = new Scanner(System.in);
        int a = scanner.nextInt();
        int b = scanner.nextInt();
        System.out.println("Before swapping: a = " + a + ", b = " + b);
        a = a + b;
        b = a - b;
        a = a - b;
        System.out.println("After swapping: a = " + a + ", b = " + b);
        scanner.close();
    }
}

```



## OUTPUT:

"C:\Users\matha\OneDrive\Pictures\Screenshots\Screenshot 2025-05-28 084745.png"



## RESULT:
Thus, the Java program to swap the values of the two variables by without using a third variable. After swapping the values should be PRINT is created successfully.
