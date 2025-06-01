# Ex.No:9(B) BYTE ARRAY I/O
## AIM:
To create a java program to write data using ByteArrayOutputStream.


## ALGORITHM :
1.	The user enters a string (data), followed by two integers (start and length) specifying the starting position and number of characters to write.
2.	The string data is converted to a byte array (array).
3.	Using ByteArrayOutputStream, it writes length bytes from array, starting at start.
4.	The written data is retrieved as a string (streamData) and displayed, showing the original input and the specific segment written to the stream.
5.	Any exceptions are caught and handled, displaying stack trace information if an error occurs.




## PROGRAM:
 ```
/*
Program to implement a BYTE ARRAY I/O using Java
Developed by: Jayasree R
RegisterNumber: 212223040074 
*/
```

```
import java.io.ByteArrayOutputStream;
import java.util.*;
public class Main 
{
    public static void main(String[] args)
    {
        try
        {
            Scanner scanner = new Scanner(System.in);
            String input = scanner.nextLine();
            byte[] byteArray = input.getBytes();
            int start = 2;
            int length = 7;
            ByteArrayOutputStream baos = new ByteArrayOutputStream();
            baos.write(byteArray, start, length);
            System.out.println("Original data: " + input);
            System.out.println("Output stream: " + baos.toString());
            baos.close();
            scanner.close();
        }
        catch(Exception e) 
        {
            e.getStackTrace();
        }
    }
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/b6a0dea5-6504-4c1d-a326-7a00c5f32f5f)

## RESULT:
Thus, java program to write data using ByteArrayOutputStream was executed and verified successfully.





