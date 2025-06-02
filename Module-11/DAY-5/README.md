# Ex.No:11(E)  JAVA HASHMAP

## AIM:
To demonstrate removing a key 100 from a HashMap and printing all remaining key-value pairs
## ALGORITHM :

a.	Import java.util.*.
b.	Create a HashMap and add some key-value pairs.
c.	Use remove(key)  to delete the entry with key 100.
d.	Iterate through the map using a for-each loop and display the entries

## PROGRAM:
 ```
/*
Program to implement a HASHMAP
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
        HashMap<Integer,String> map=new HashMap<Integer,String>();
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
    Integer key=100;
    String value=map.get(key);
    System.out.println("Following value is removed from Map: "+value);
    }
}
```





## OUTPUT:


![image](https://github.com/user-attachments/assets/71581a47-18b4-43c8-92fd-ef17466dc193)


## RESULT:
Thus the java program was successfully removes the key 100 from the HashMap and displays the remaining key-value pairs.




