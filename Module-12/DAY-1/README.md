# Ex.No:12(A)         JAVA TREE MAP
## AIM:
 To implement a Java program to associate the specified value with the specified key in a Tree Map.

## ALGORITHM :

1.	Start the Program
2.	Import `java.util.*` and `java.util.Map.Entry`
3.	Define `Example6` class with `main` method:
-	a) Initialize `TreeMap<String, String> tree_map1`
-	b) Read integer `size` for entries count.
4.	Use a loop to:
-	a) Read `String` values `n1` and `s1`
-	b) Insert each pair into `tree_map1`
5.	Print `tree_map1` as `"Original TreeMap content: "`
6.	Define `sort_key` class that implements `Comparator<String>`:
-	Override `compare` method to compare `String` values `str1` and `str2` using
`compareTo`
7.	End



## PROGRAM:
 ```
/*
Program to implement a JAVA TREE MAP using Java
Developed by: Jayasree R
RegisterNumber: 212223040074 
*/
```
```
import java.util.*;
public class Example6 {  
    public static void main(String[] args){  

   TreeMap<Integer,String> tree_map1 = new TreeMap<Integer,String>();      
  Scanner sc=new Scanner(System.in);
   int size=sc.nextInt();
   for(int i=0;i<size;i++)
   {
      Integer n1 = sc.nextInt();
      String s1= sc.next();
       
   	  tree_map1.put(n1,s1);  
   }
    

  System.out.println("Orginal TreeMap content: " + tree_map1);
  System.out.println("Greatest key: " + tree_map1.firstEntry());
  System.out.println("Least key: "+tree_map1.lastEntry());
    }
}

```




## OUTPUT:


![image](https://github.com/user-attachments/assets/8ea927ef-1acc-4952-812e-22cb74fa757f)


## RESULT:
Thus the Java program to associate the specified value with the specified key in a Tree Map was executed successfully.
