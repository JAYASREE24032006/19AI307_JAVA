# Ex.No:5(D) IS-A RELATIONSHIP AND HAS-A RELATIONSHIP
## AIM:
   To Create a java program to find factorial of number using class and object concepts and apply the has-a relationship.
 
## ALGORITHM :
1.	Start the Program
2.	Define class `A`:
-	a) Declare integer `n` and initialize `fact` to 1
-	b) Define method `factorial(int n)`:
-	i) Set `this.n = n`
-	ii) Use a loop from 1 to `n` to calculate `fact = fact * i`
-	iii) Print "Factorial is:" followed by `fact`
3.	In `main` class `main` method:
-	a) Use `Scanner` to read integer `n`
-	b) Create an `A` object and call `factorial(n)`
4.	End

## PROGRAM:
 ```
/*
Program to implement a IS-A RELATIONSHIP AND HAS-A RELATIONSHIP using Java
Developed by: R.Jayasree
RegisterNumber:  212223040074
*/
```
```
import java.util.Scanner;
class factorial{
    int fact(int a) {
        int i, f = 1;
        for (i = 1; i <= a; i++) {
            f = f * i;
        }
        return f;
    }
}
public class Main {
    public static void main(String args[]) {
        int a, f;
        Scanner sc = new Scanner(System.in);
        a = sc.nextInt();
        factorial ff = new factorial();
        f = ff.fact(a);
        System.out.println("Factorial is:" + f);
    }
}
```



## OUTPUT:

![image](https://github.com/user-attachments/assets/12a22bb4-72da-4159-ac7b-baf7be50dac0)


## RESULT:
Thus the java program to find factorial of number using class and object concepts and apply the has-a relationship was executed successfully.
