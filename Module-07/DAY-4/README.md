# Ex.No:7(D) SYNCHRONIZATION
## AIM:
 To Develop a Java Program to perform static synchronization method for the below Scenario Create a Class Display with synchronized void wish method in that perform "Welcome : Message. Note :Assume Sleep as 400 ms i.e Thread.Sleep(400)
 
## ALGORITHM :
1.	1.	Start the Program.
2.	Define class `Display`:
-	a) Create a `Scanner` object `sc` for input
-	b) Define a synchronized method `wish(String str)`:
- i) Print "Welcome :: " followed by `str` (twice)
3.	End



## PROGRAM:
 ```
/*
Program to implement a Packages using Java
Developed by: Jayasree R
RegisterNumber: 212223040074 
*/
```
```
class Display 
{
    public static synchronized void wish(String msg) 
    {
        for (int i = 0; i < 2; i++)
        {
            System.out.println("Welcome :: " + msg);
            try
            {
                Thread.sleep(400);  
            } 
            catch (InterruptedException e)
            {
                System.out.println("Thread interrupted");
            }
        }
    }
}
class MessageThread extends Thread 
{
    private String message;
    public MessageThread(String msg) 
    {
        this.message = msg;
    }
    @Override
    public void run() 
    {
        Display.wish(message);  
    }
}
class Main 
{
    public static void main(String[] args) throws InterruptedException
    {
        String[] testMessages = {"Saveetha College", "Anna University"};
        MessageThread t1 = new MessageThread(testMessages[0]);
        MessageThread t2 = new MessageThread(testMessages[1]);
        t1.start();
        t2.start();
        t1.join();  
        t2.join();
    }
}

```





## OUTPUT:

![image](https://github.com/user-attachments/assets/fab43c3f-3a0b-493c-b0ef-f06047478e14)



## RESULT:
Thus the java program for synchronization was executed successfully.

