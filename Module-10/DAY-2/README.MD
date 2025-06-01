# Ex.No:10(B) JAVA LINKED LIST
## AIM :
To Create a java program to perform linkedlist, read size of the list , read the elements for the linkedlist and display the elements from the linkedlist.


## ALGORITHM :
1.	Start the Program
2.	Import `java.util.*` for input handling and list functionality
3.	Define class `Hello` with the `main` method:
-	a) Create `Scanner` object `sc` for input
-	b) Read an integer `n` to specify the number of strings
-	c) Create a `LinkedList` named `str` to store strings
4.	Use a `for` loop to:
-	a) Read `n` strings from input and add each to `str`
5.	Print the entire `str` list
6.	End



## PROGRAM:
 ```
/*
Program to implement a JAVA LINKED LIST using Java
Developed by: Jayasree R
RegisterNumber:  212223040074
*/

```
```
import java.util.*;

public class Main {
  public static void main(String[] args) {
   Scanner sc=new Scanner(System.in);
    LinkedList<String> cars = new LinkedList<String>();
    int n=sc.nextInt();
    for(int i=0;i<n;i++)
    {
    cars.add(sc.next());
    }
    
    System.out.println("Linked List :" +cars);
    System.out.println("Linked List size:" + cars.size());
  }
}

```





## OUTPUT:
![image](https://github.com/user-attachments/assets/b3c49817-6e37-40fe-b6f6-3eb81fc56845)


## RESULT:
Thus the Java program of the creation of a linkedlist was executed successfully.





