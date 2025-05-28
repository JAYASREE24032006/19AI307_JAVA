# Ex.No:2(D) MULTI-DIMENSIONAL ARRAY

## AIM:
To create a java program that copy one array value to another value in Java by using the assignment operator (=).

## ALGORITHM :
1.Start

2.Input the number of elements n and read n integers into the array array[].

3.Initialize a second array newArr[] of the same size.

4.Copy each element from array[i] to newArr[i] using a loop.

5.Output both the original and copied arrays.
## PROGRAM:
 ```
/*
Program to implement a Multi Dimensional Array using Java
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
int n;  
Scanner sc=new Scanner(System.in);  
n=sc.nextInt();  
int[] array = new int[10];  
int[] newArr = new int[10]; 
for(int i=0; i<n; i++)  
{  
array[i]=sc.nextInt();  
}  
for(int i=0; i<n; i++)  
{  
newArr[i]=array[i];  
} 
System.out.println("Original Array=" + Arrays.toString(array));
System.out.println("Copied Array=" + Arrays.toString(newArr));
}
}import java.util.*;  
public class Main  
{  
public static void main(String[] args)   
{  
int n;  
Scanner sc=new Scanner(System.in);  
n=sc.nextInt();  
int[] array = new int[10];  
int[] newArr = new int[10]; 
for(int i=0; i<n; i++)  
{  
array[i]=sc.nextInt();  
}  
for(int i=0; i<n; i++)  
{  
newArr[i]=array[i];  
} 
System.out.println("Original Array=" + Arrays.toString(array));
System.out.println("Copied Array=" + Arrays.toString(newArr));
}
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/837f2165-2ba1-4bab-940f-5252af8f523c)


## RESULT:
Thus the java program that  program copy one array value to another value in Java by using the assignment operator (=). was executed successfully.


