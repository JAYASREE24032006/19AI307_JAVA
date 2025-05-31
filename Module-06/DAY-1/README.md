# Ex.No:6(A)  INNER CLASS
## AIM:
To create a Java Program to implement Method Local Inner Class.

## ALGORITHM :
1.  Start the Program.
2.	Define outer class `name`:
-	a) Declare `String name` and initialize it to "Johnson"
-	b) Define inner class `inner`:
- i) Define method `display()` that prints "Name given in Outer Class is " followed by `name`
3.	In the `main` method of `name` class:
-	a) Create an instance `obj` of the `name` class
-	b) Create an instance `obj2` of the inner class `inner` using `obj`
-	c) Call `display()` on `obj2` to print the outer class name
4.	End






## PROGRAM:
 ```
/*
Program to implement a Inner Class using Java
Developed by: jayasree R
RegisterNumber:  212223040074
*/
```
```
public class MethodLocal 
{
    String outerValue = "Outer Class Variable";
    public void display() 
    {
        String innerValue = "Inner Class Variable";
        class Inner
        {
            public void print() 
            {
                System.out.println(outerValue);
                System.out.println(innerValue);
            }
        }
        Inner inner = new Inner();
        inner.print();
    }
    public static void main(String[] args) 
    {
        MethodLocal methodLocal = new MethodLocal();
        methodLocal.display();
    }
}

```





## OUTPUT:
![image](https://github.com/user-attachments/assets/ffb5f558-b19d-4ed4-973a-d5c46b55bc41)



## RESULT:
Thus, the Java Program using Method Local Inner Class was executed successfully.

