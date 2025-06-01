# Ex.No:10(A)         JAVA COLLECTION FRAMEWORK –ARRAY LIST
## AIM:
 To Create a arraylist and add odd numbers from 30 to 11 and then display the result in sorting order.

## ALGORITHM:
1.	Start the Program
2.	Import `java.util.*` for input handling and list functionality
3.	Define class `Snowdrop` with the `main` method:
-	a) Create `Scanner` object `sc` for input
-	b) Read an integer `n` to specify the number of elements
-	c) Create an `ArrayList` named `num` to store integers
4.	Use a `for` loop to:
-	a) Read `n` integers from input and add each to `num`
5.	Use an enhanced `for` loop to:
-	a) Iterate through `num` and print each element
6.	End

## PROGRAM:
 ```
/*
Program to implement a ARRAY LIST using Java
Developed by: Jayasree R
RegisterNumber:  212223040074
*/
```

```
import java.util.*;  
public class Main 
{
  public static void main(String[] args)
  {
    ArrayList<Integer> arraylist = new ArrayList<Integer>();
    arraylist.add(29);
    arraylist.add(27);
    arraylist.add(25);
    arraylist.add(23);
    arraylist.add(21);
    arraylist.add(19);
    arraylist.add(17);
    arraylist.add(15);
    arraylist.add(13);
    arraylist.add(11);
    Collections.sort(arraylist);
    System.out.println(arraylist);
   }
}
```



## OUTPUT:
![image](https://github.com/user-attachments/assets/63903dc2-27af-4a8b-9203-e5606312a250)



## RESULT:
TThus the Java Program to store n numbers (add elements of type Integer) and then display the n numbers using array List was executed successfully.

