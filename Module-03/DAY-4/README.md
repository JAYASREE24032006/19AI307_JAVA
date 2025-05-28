# Ex.No:3(D) STRING TOKENIZER IN JAVA

## AIM:
To create a java program using StringTokenizer class that tokenizes a string "My name is Java Programming" on the basis of whitespace.

## ALGORITHM :
1.	Start the Program
2.	Import `Scanner` and `StringTokenizer` and define class `tok`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Initialize the string `str` as "My name is Java Programming"
4.	Create a `StringTokenizer` object `token` to tokenize `str`
5.	Use a `while` loop to iterate through tokens:
-	a) Print each token using `token.nextToken()`
6.	End




## PROGRAM:
 ```
/*
Program to implement a String Tokenizer using Java
Developed by: jayasree R
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
        String ch="My name is Java Programming";
        String[] ac=ch.split(" ");
        for(String a:ac)
        {
            System.out.println(a);
        }
    }
}
```




## OUTPUT:


![image](https://github.com/user-attachments/assets/b97bd61b-7d38-4c9c-8831-61e86b33a3b8)


## RESULT:
Thus the java program using StringTokenizer class that tokenizes a string "My name is Java Programming" on the basis of whitespace was executed successfully.
