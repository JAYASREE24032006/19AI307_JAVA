# Ex.No:9(C)             STRING READER
## AIM:
 To Create a Java Program to display and skip the specified number of characters using the predefined Method Skip in StringReader


## ALGORITHM :
1.  The user enters a string (data) and an integer (skipnumber) indicating the number of characters to skip.
2.	The original string is displayed for reference.
3.	A StringReader object, input, is created to read from data.
4.	The program skips the specified number of characters (skipnumber) in the string.
5.	It reads and displays the remaining characters one by one until the end of the string.
6.	Any exceptions are caught, and stack trace information is generated if an error occurs.


## PROGRAM:
 ```
/*
Program to implement a String Reader using Java
Developed by: Jayasree R
RegisterNumber:212223040074
*/
```
```
import java.io.*;
public class StringSkipExample
{
    public static void main(String[] args) 
    {
        BufferedReader reader = new BufferedReader(new InputStreamReader(System.in));
        try 
        {
            String inputString = reader.readLine();
            int a = Integer.parseInt(reader.readLine());
            StringReader stringReader = new StringReader(inputString);
            stringReader.skip(a);
            StringBuffer result = new StringBuffer();
            int character;
            while ((character = stringReader.read()) != -1) 
            {
                result.append((char) character);
            }
            System.out.println("Original data: " + inputString);
            System.out.println("Data after skipping "+a+" characters:");
            System.out.println(result.toString());
            stringReader.close();
        } 
        catch (IOException e) 
        {
            System.out.println("Error reading input: " + e.getMessage());
        }
    }
}

```




## OUTPUT:

![image](https://github.com/user-attachments/assets/9ca3cd24-0f66-480b-b721-1d3bc35a3134)


## RESULT:
Thus the Java Program to display and skip the specified number of characters using the predefined Method Skip in StringReader was executed and verified successfully.











