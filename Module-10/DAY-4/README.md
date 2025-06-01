# Ex.No:10(D) JAVA HASHSET & LINKEDHASHSET

## AIM:
 To create a java program use hashset concepts in collection and add the elements to the hashset and then display the elements iterate(use while) in an unordered collection.


## ALGORITHM :
1.	Start the Program.
2.	Import `java.util.*`
3.	Define class `Main` with `main` method:
-	a) Initialize `Scanner` and read integer `n`
-	b) Create a `HashSet` named `hs` to store unique strings
4.	Use a loop to read `n` strings and add each to `hs`
5.	Use an enhanced `for` loop to print each element in `hs`
6.	End



## PROGRAM:
 ```
/*
Program to implement a JAVA HASHSET & LINKEDHASHSET using Java
Developed by: Jayasree R
RegisterNumber:  212223040074
*/
```
```
import java.util.*;

public class HashSetDemo{

public static void main(String args[]){

LinkedHashSet <String> hs = new LinkedHashSet <String>();
Scanner sc=new Scanner(System.in);
int n=sc.nextInt();
for(int i=0;i<n;i++)
{
    
hs.add(sc.next());

}

Iterator<String> it = hs.iterator();
		while (it.hasNext())
			System.out.println(it.next());
}
}
```





## OUTPUT:

![image](https://github.com/user-attachments/assets/acccab61-841e-4c2f-98a2-39de148721cc)


## RESULT:
Thus the java program of hashmap concepts was executed and verified successfully.



