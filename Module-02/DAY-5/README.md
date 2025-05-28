# Ex.No:2(E)  SUM OF ELEMENT IN AN ARRAY

## AIM:
To write a Java program to find the sum of all the elements present in a 2-D array..
## ALGORITHM :
1.	Start the program.
2.	Read the size of the array from the user.
3.	Declare an array of the given size.
4.	Read the array elements from the user.
5.	Initialize a variable min with the first element of the array.
6.	Traverse the array using a loop.
7.	Compare each element with min. If an element is smaller, update min.
8.	After the loop ends, print the smallest number.
9.	End the program.
	

## PROGRAM:
 ```
/*
Program to implement a Smallest Element in an Array
Developed by: Jayasree R
RegisterNumber:  212223040074
*/
```
```

import java.util.Scanner;
public class demo
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int n = sc.nextInt();
        int sum=0;
        for(int i=1;i<=n;i++)
        {
            int a=sc.nextInt();
            sum+=a;
        }
        System.out.println("Sum of an array:");
        System.out.println(sum);
    }
}
```



## OUTPUT:
![image](https://github.com/user-attachments/assets/86785a38-fed6-42d4-b468-d9098a792b42)



## RESULT:
Thus the java program to find the sum of all the elements present in a 2-D array is successfukky executed.




