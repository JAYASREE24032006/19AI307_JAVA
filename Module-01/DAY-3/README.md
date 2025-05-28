# Ex.No:1(C) CONTROL STATEMENTS

## AIM:
To develop a Java program to to Take three numbers from the user and print the greatest number.
## ALGORITHM:
1.	Start the program.
2.	Declare an integer variable a,b and c.
3.	Create a Scanner object 'sc' to read input from the user
4.	Read an integer input from the user and store it in 'num'
5.	Check the greater number among these numbers.
6.	End





## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: Jayasree R
RegisterNumber:  212223040074
*/
```

```
import java.util.Scanner;
public class great
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int a = sc.nextInt();
        int b = sc.nextInt();
        int c = sc.nextInt();
        if (a>b && a>c)
        {
            System.out.println(a+ " is the Greatest value");
        }
        else if (c>b && c>a)
        {
            System.out.println(c+ " is the Greatest value");
        }
        else
        {
            System.out.println(b+ " is the Greatest value");
        }
    }
}

```




## OUTPUT:
![image](https://github.com/user-attachments/assets/2d976475-a553-402d-a064-84e5f5ac951f)

## RESULT:
Thus the  Java program to to Take three numbers from the user and print the greatest number is executed Successfully.


## RESULT:
Thus, the Java program to check given number is zero or not was created successfully.

