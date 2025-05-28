# Ex.No:2(C)    SINGLE ARRAY

## AIM:
To create a java program to Develop a Java Program to sort the elements of an array in descending order.

## ALGORITHM :
1.Start

2.Input the size of the array (size) and the array elements from the user.

3.Store the elements into an Integer[] array.

4.Sort the array in descending order using Arrays.sort(array, Collections.reverseOrder()).

5.Output the sorted array elements.




## PROGRAM:
 ```
/*
Program to implement a Single Array using Java
Developed by: Jayasree R
RegisterNumber:  212223040074
*/
```

```
import java.util.Arrays;
import java.util.Collections;
import java.util.Scanner;
public class SortArrayDescending 
{
    public static void main(String[] args) 
    {
        Scanner scanner = new Scanner(System.in);
        int size = scanner.nextInt();
        Integer[] array = new Integer[size];
        for (int i = 0; i < size; i++)
        {
            array[i] = scanner.nextInt();
        }
        Arrays.sort(array, Collections.reverseOrder());
        System.out.print("Result of a Sorted Array :");
        for (int i = 0; i < size; i++) 
        {
            System.out.print(array[i] + " ");
        }
    }
}
```







## OUTPUT:
![image](https://github.com/user-attachments/assets/30064c7b-fd8c-46fa-ab5b-b60cd1b3cddd)



## RESULT:
Thus, the Java program Thus the java program to sort the elements of an array in descending order array using single dimensional  was executed successfully.


