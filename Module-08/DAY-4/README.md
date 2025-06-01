# Ex.No:8(D) BUFFER INPUT/OUTPUT STREAM

## AIM:
 To create a java program file for displaying the data from the file after skip method using FileInputStream & BufferedInputStream.

## ALGORITHM :
1.	Import java.io.* and java.util.* for file handling and user input.
2.	Create a file named sample.txt and write "This is a line of text inside the file." using FileWriter.
3.	Close the FileWriter to save the content to sample.txt.
4.	Open sample.txt with a FileInputStream wrapped in a BufferedInputStream for efficient reading.
5.	Prompt the user to enter the number of bytes to skip using Scanner.
6.	Skip the specified number of bytes in the file and print the remaining content.
7.	Close the BufferedInputStream and FileInputStream to release system resources.




## PROGRAM:
 ```
/*
Program to implement a Buffer Input/Output Stream using Java
Developed by: Jayasree R
RegisterNumber: 212223040074 
*/
```
```
try {
            // Open the file sample.txt
            FileInputStream fileInput = new FileInputStream("sample.txt");
            BufferedInputStream bufferedInput = new BufferedInputStream(fileInput);

            int i;
            System.out.println("Data in the File:");
            while ((i = bufferedInput.read()) != -1) {
                System.out.print((char) i);
            }

            // Close streams
            bufferedInput.close();
            fileInput.close();
        } catch (IOException e) {
            System.out.println("An error occurred: " + e.getMessage());
        }
```







## OUTPUT:

![image](https://github.com/user-attachments/assets/2c58327f-7727-4615-980f-0d5b08d58f63)



## RESULT:
Thus, the java program file for displaying the data from the file after skip method using FileInputStream & BufferedInputStream was executed and done successfully.


