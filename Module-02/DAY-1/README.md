# Ex.No:2(A)  STATIC METHOD

## AIM:
To create a java Program to Reverse a Number Using static function.

## ALGORITHM :
1.Start

2.Input an integer num from the user.

3.Initialize reversed = 0.
4.While num is not 0:

5.Get the last digit using digit = num % 10

6.Update reversed number: reversed = reversed * 10 + digit

7.Remove the last digit from num using num = num / 10

8.Output the reversed number.

9.Stop


## PROGRAM:
 ```
/*
Program to implement a Static method using Java
Developed by: Jayasree R
RegisterNumber:  212223040074
*/
```

```
import java.util.Scanner;
public class NumberReverser
{
    public static int reverseNumber(int number)
    {
        int reversed = 0;
        while (number != 0) 
        {
            int digit = number % 10;
            reversed = reversed * 10 + digit;
            number /= 10;
        }
        return reversed;
    }
    public static void main(String[] args) 
    {
        Scanner scanner = new Scanner(System.in);
        int num = scanner.nextInt();
        int reversedNum = reverseNumber(num);
        System.out.println("Reversed number: " + reversedNum);
    }
}

```





## OUTPUT:

![image](https://github.com/user-attachments/assets/73c51510-683d-4f1b-8c78-963940299c92)


## RESULT:
Thus the java program to Reverse a Number Using static function has been executed successfully.

