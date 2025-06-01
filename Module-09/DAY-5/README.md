# Ex.No:9(E) STRING WRITER

## AIM:
To write a Java program that reads a string from the user and prints it using the StringWriter class.
## ALGORITHM :

a.	Start the program.
b.	Import java.io.* and java.util.Scanner.
c.	Create a Scanner object to read input from the user.
d.	Read a string from the user.
e.	Create a StringWriter object.
f.	Write the string to the StringWriter object.
g.	Convert the StringWriter content to a string using .toString().
h.	Print the result on the output screen.
i.	Close the writer.
j.	End the program.


## PROGRAM:
 ```
/*
Program to implement a STRING WRITER
Developed by: Jayasree R
RegisterNumber: 212223040074 
*/
```
```
import java.io.StringWriter;
public class Main
{
    public static void main(String[] args) 
    {
        String data = "This is the text in the string.";
        try
        {
            StringWriter si=new StringWriter();
            System.out.print("Data in the StringWriter: ");
            si.write(data);
            System.out.println(si);
            si.close();
        }
        catch(Exception e) 
        {
            e.getStackTrace();
        }
    }
}
```


## OUTPUT:
![image](https://github.com/user-attachments/assets/e5dd3cdd-dab5-4e7f-93bb-f5b67361ab30)



## RESULT:
Thus, implementation of  a Java program was successfully reads a string from the user and uses StringWriter to write and print the string to the output screen.

