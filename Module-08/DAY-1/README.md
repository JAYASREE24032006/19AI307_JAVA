# Ex.No:8(A)           IO-FILE STREAM
## AIM:
To implement a Java Program to write a byte in a file "testout.txt" using FileOutputStream

## ALGORITHM :
1.  Define the string "Welcome to Saveetha" and convert it to a byte array b using getBytes().
2.	Use Scanner to prompt the user for start (starting index) and length (number of bytes) to write from the string.
3.	Open testout.txt using FileOutputStream, and write the specified portion of b from the start index for length bytes, then close the output stream.
4.	Open testout.txt using FileInputStream, read its contents byte-by-byte, convert each byte to a character, and print it to display the file's content.
5.	Use file.delete() to delete testout.txt.
6.	Attempt to read the deleted file, which triggers a FileNotFoundException as the file no longer exists.


## PROGRAM:
 ```
/*
Program to implement a IO File Stream using Java
Developed by: Jayasree R
RegisterNumber:  212223040074
*/
```
```
try
{
    FileOutputStream fout=new FileOutputStream("testout.txt");    
    fout.write(65);    
    fout.close();    
    System.out.println("Successfully Completed"); 
}
catch(Exception e)
{
    System.out.println(e);
}

```




## OUTPUT:


![image](https://github.com/user-attachments/assets/2b8ed683-9051-42a1-93e5-12e09623c4c6)


## RESULT:
Thus the implementation of a Java Program to write a String in a file "testout.txt" using FileOutputStream was executed and verified successfully

