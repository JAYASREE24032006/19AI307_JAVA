# Ex.No:11(B)   JAVA MAP & HASHMAP AND HASHTABLE
## AIM :
To Create a java program to retrieve the key and value from hashtable for all input value.

## ALGORITHM :

1.	Start
2.	Import `java.util.*`
3.	Define class `A` with `main` method:
-	a) Initialize `Scanner` and read integer `n`
-	b) Create a `Hashtable` named `hash` to store integer keys and string values
4.	Use a loop to:
-	a) Read an integer and string from the user
-	b) Add the integer as the key and the string as the value in `hash`
5.	Use an enhanced `for` loop to iterate through `hash` and print each key-value pair
6.	End




## PROGRAM:
 ```
/*
Program to implement a JAVA MAP & HASHMAP AND HASHTABLE using Java
Developed by: Jayasree R
RegisterNumber:  212223040074
*/
```

```

import java.util.*;  
public class Mapp{  
 public static void main(String args[]){ 
     
  Map<Integer,String> map=new Hashtable<>(); 
  Scanner sc=new Scanner(System.in);
  
  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  Integer a=sc.nextInt();
  String b=sc.next();
  map.put(a,b);  
  } 
 
  for(Map.Entry m:map.entrySet()){  
   System.out.println(m.getKey()+" "+m.getValue());  
  }  
  boolean isEmpty = map.isEmpty(); System.out.println("Is HashMap is empty: " + isEmpty);
 }  
}  
```




## OUTPUT:

![image](https://github.com/user-attachments/assets/0ae7ae4a-0075-473b-8dd7-ea590f555f3b)


## RESULT:
Thus the java program to retrieve the key and value from hashtable for all input value was executed successfully.







