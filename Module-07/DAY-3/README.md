# Ex.No:7(C)             THREAD IN JAVA
## AIM:
 To Develop a Java program to create Thread using Thread class.


## ALGORITHM :
1.  Start the Program
2.	Import necessary classes: `java.util.*`
3.	Define a class `Multi` that extends `Thread`:
-	a) Create a `Scanner` instance for user input.
-	b) Override the `run` method:
-	i) Read a string from user input.
-	ii) Print "Thread Name:" followed by the input string.
4.	In the `main` method:
-	a) Create an instance of `Multi`.
-	b) Create a new `Thread` instance using the `Multi` object.
-	c) Start the thread with `t1.start()`.
5.	End





## PROGRAM:
 ```
/*
Program to implement a Thread concepts using Java
Developed by: Jayasree R
RegisterNumber:  212223040074
*/
```
```
import java.util.*;
    public class Multi implements Runnable
    {  
        Scanner sc=new Scanner(System.in);
        
    public void run()
    {  
        int number=sc.nextInt();
        int remainder=0,reverse=0,temp;
        temp=number;
       while(number != 0)   
        {  
         remainder = number % 10;  
        reverse = reverse * 10 + remainder;  
        number = number/10;  
        }  
        if(temp==reverse)
        {
        System.out.println("The number " +temp+" is Palindrome");  
        }
        else
        {
              System.out.println("The number " +temp+" is not a Palindrome");  
        }
    }  
    public static void main(String args[]){  
    Multi m1=new Multi(); 
    Thread t1 =new Thread(m1); 
    t1.run();  
     }  
    }
```





## OUTPUT:


![image](https://github.com/user-attachments/assets/75c819e1-37e6-41ff-a30b-29effc9504dc)


## RESULT:
Thus the Java program for the creation of Thread using Thread class was executed successfully.







