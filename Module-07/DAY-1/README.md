# Ex.No:7(A)           EXCEPTION HANDLING-RUN TIME EXCEPTION
## AIM:
  To Develop a Java Program for handling Arithmetic Exception (division by zero exception) using Exception Handling Mechanism.

## ALGORITHM :
1.  Start the Program
2.	Import `java.util.*` for input handling
3.	Define class `Example1`:
-	a) In `main` method, create `Scanner` object `sc` for input
4.	Use `try` block to:
-	a) Read integers `a` and `b` from user input
-	b) Calculate `res = a / b` and print "Result: " followed by `res`
5.	Use `catch` block to handle `ArithmeticException`:
-	a) If division by zero occurs, print "You Shouldn't divide a number by zero"
6.	End







## PROGRAM:
 ```
/*
Program to implement a Exception Handling-Run Time Exception using Java
Developed by: Jayasree R
RegisterNumber: 212223040074 
*/
```

```
import java.util.*;
class Exception2 
{
   public static void main(String args[])
   {
     Scanner sc=new Scanner(System.in);
      try {
         int a[]=new int[5];
       
         int n=sc.nextInt();
          System.out.println("Valid Statement :" +a[n]);
         // another try block
         try {
                 int res = 100/ n;
         }
         catch (ArithmeticException ex2) {
            System.out.println("Sorry! Division by zero isn't feasible!");
         }
      }
      catch (ArrayIndexOutOfBoundsException ex1) {
         System.out.println("ArrayIndexOutOfBoundsException");
      }
   }
}

```




## OUTPUT:


![image](https://github.com/user-attachments/assets/92c8ba51-8a70-40bb-bc9f-d7c2571a8ba6)

## RESULT:
Thus the Java Program for handling Arithmetic Exception (division by zero exception) using Exception Handling Mechanism was executed successfully.

