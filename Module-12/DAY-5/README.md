# Ex.No:12(E)  JAVA DEQUEUE

## AIM:
To demonstrate how to remove and display the first element from a Deque using the pollFirst() method in Java Collections with String values.
## ALGORITHM :

1.	Import java.util.*.
2.	Create a Deque using LinkedList.
3.	Add several string elements to the deque.
4.	Use pollFirst() to remove and return the first element.
5.	Print the removed element.
6.	Display the remaining elements in the deque.

## PROGRAM:
 ```
/*
Program to implement a JAVA DEQUEUE
Developed by: Jayasree R
RegisterNumber:  212223040074
*/
```

```
import java.util.*;
public class main
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        Deque<String> al=new LinkedList<String>();
        for(int i=0;i<n;i++)
        {
            al.add(sc.next());
        }
        System.out.println("Display the element of Dequeue:");
        System.out.println(al);
        System.out.println(al.pollFirst());
    }
}
```



## OUTPUT:


![image](https://github.com/user-attachments/assets/f30bb8da-ade9-4831-aa1c-b5913cdece02)


## RESULT:

Thus the java program successfully demonstrates how to use pollFirst() to remove and display the first element from a Deque of strings.


