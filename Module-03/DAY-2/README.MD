# Ex.No:3(B) STRING BUFFER IN JAVA

## AIM:
To develop a java program use append() method concatenates the given argument with this String and use stringbuffer class.

## ALGORITHM :
1.	Start the program.
2.	Import `Scanner` and define class `concat`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read two strings `a` and `b` from user input
4.	Create a `StringBuffer` object `sb` initialized with string `a`
5.	Append a space and string `b` to `sb`
6.	Print the concatenated result from `sb`
7.	End







## PROGRAM:
 ```
/*
Program to implement a String Buffer using Java
Developed by: Jayasree R
RegisterNumber:  212223040074
*/
```
```
import java.util.*;
public class StringBufferExample
{  
    public static void main(String args[])
    {  
        Scanner sc=new Scanner(System.in);
        String str1=sc.nextLine();
        String str2=sc.nextLine();
        StringBuffer sb=new StringBuffer(str1);  
        sb.append(" "+str2);  
        System.out.println(sb);  
    }  
}  
```



## OUTPUT:

```
Input : Hello
        Java

Output : Hello Java

```



## RESULT:
Thus the java program use append() method concatenates the given argument with this String and use stringbuffer class was executed successfully.
