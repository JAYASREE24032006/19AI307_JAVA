# Ex.No:3(C)    STRING BUILDER IN JAVA

## AIM:
To Create a java program use replace() method replaces the given String from the specified beginIndex and endIndex and use stringbuilder

## ALGORITHM :
1.  Start the Program
2.	Import `Scanner` and define class `replace`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read a string `str` from user input
4.	Create a `StringBuilder` object `sb` initialized with `str`
5.	Use the `replace()` method to replace characters from index 1 to 3 with "Java"
6.	Print the modified string using `sb.toString()`
7.	End






## PROGRAM:
 ```
/*
Program to implement a String Builder using Java
Developed by: Jayasree R
RegisterNumber: 212223040074 
*/
```

```
import java.util.Scanner;
public class demo
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        String ch=sc.nextLine();
        if(ch.length()>=4)
        {
            System.out.println(ch.charAt(0)+"Java"+ch.substring(3,ch.length()));
        }
        else
        {
            System.out.println(ch.charAt(0)+"Java");
        }
    }
}
```



## OUTPUT:

![image](https://github.com/user-attachments/assets/249e2cd4-2d56-4463-85bc-b7bac778a66e)



## RESULT:
Thus the java program use replace() method replaces the given String from the specified beginIndex and endIndex and use stringbuilder was executed successfully.



