# Ex.No:11(D) RELATED TO MAP CONCEPTS

## AIM:
To Create a java program to insert and display the key and values using map interface.

## ALGORITHM :

1.	Start
2.	Import `java.util.*`
3.	Define class `Deivamagal` with `main` method:
-	a) Read integer `n` (number of entries).
-	b) Create a `HashMap` `hash`.
4.	Loop to read key-value pairs and add to `hash`.
5.	Print `"Map: " + hash`, keys, values, and entries.
6.	End




## PROGRAM:
 ```
/*
Program to implement a RELATED TO MAP CONCEPTS using Java
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
        Map<Integer,String> map=new HashMap<Integer,String>();
        for(int i=0;i<n;i++)
        {
            Integer a=sc.nextInt();
            String b=sc.next();
            map.put(a,b);
        }
        for(Map.Entry m:map.entrySet())
        {
            System.out.println("key: "+m.getKey()+" value: "+m.getValue());
        }
    }
}
```





## OUTPUT:

![image](https://github.com/user-attachments/assets/ef1e2686-191e-47dd-b777-85403a13c154)



## RESULT:
Thus the java program to insert and display the key and values using map interface was  executed and verified successfully.


