# Ex.No:2(B) ACCESS MODIFIERS

## AIM:
To develop a Java Program to display the product of  number using private modifiers only.

## ALGORITHM:
1.	Start the program.
2.	Define a class named `addition`
3.	Declare two private integer variables, `num1` and `num2`
4.	Define a private method `add()` that:
a)	Returns the sum of `num1` and `num2`
5.	Define a public method `display(int n1, int n2)` that:
a)	Assigns `n1` to `num1` and `n2` to `num2`
b)	Calls the `mul()` method and prints the result using `System.out.println`
6.	Define the `main` method as static
a)	Create an instance of the `product` class called `ad`
b)	Call the `display(8, 9)` method on the `ad` object
7.	End






## PROGRAM:
 ```

Program to implement a access modifiers using Java
Developed by: 
RegisterNumber:  

```

```
import java.util.Scanner;
public class demo
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        int b=sc.nextInt();
        int pro = a*b;
        System.out.println("Output: "+pro);
    }
}
```







## OUTPUT:
```
Input : 5,5
Output : 25
```


## RESULT:
Thus the java program to display the product if  number using private modifiers only was executed successfully.


