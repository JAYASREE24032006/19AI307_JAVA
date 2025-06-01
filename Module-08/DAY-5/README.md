# Ex.No:8(E)  INPUT STREAM READER.

## AIM:
To write a Java Program for Reading data from console by InputStreamReader and BufferedReader
## ALGORITHM :
1.Start the program.

2.Create a BufferedReader object to read input from the user using InputStreamReader(System.in).

3.Read a string input from the user using readLine() and store it in a variable.

4.Display a welcome message by concatenating "Welcome: " with the user input.

5.Handle exceptions using a try-catch block to catch and print any input/output errors

## PROGRAM:
 ```
/*
Program to implement a INPUT STREAM READER
Developed by: Jayasree R
RegisterNumber: 212223040074 
*/
```

```
import java.util.Scanner;
import java.io.*;
public class demo
{
    public static void main(String[] args)
    {
        try 
        {
            BufferedReader bf=new BufferedReader(new InputStreamReader(System.in));
            String s=bf.readLine();
            System.out.println("Welcome: "+s);
        }
        catch(Exception e)
        {
            System.out.println(e);
        }
    }
}
```




## OUTPUT:

![image](https://github.com/user-attachments/assets/73946534-9e6c-477a-9e8e-9958826ba7d0)



## RESULT:
Thus, the java program uses InputStreamReader to read input and handles loop termination based on the presence of # at the end of the input string, as specified. 

