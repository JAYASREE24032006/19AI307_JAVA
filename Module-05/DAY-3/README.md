# Ex.No:5(C)    GETTER AND SETTER METHOD

## AIM:
To Create a java program to print the sum of two number using getter and setter method.

## ALGORITHM :
1.  Start the Program
2.	Define class `Employee`:
-	a) Private variables `n1` and `n2`
-	b) Method `setsum(int n1, int n2)` to set values of `n1` and `n2`
-	c) Method `getsum()` to calculate and print `sum = n1 + n2`
3.	In `main` class `main` method:
-	a) Use `Scanner` to read integers `n1` and `n2`
-	b) Create ` Employee ` object, set values, and call `getsum()`
4.	End


## PROGRAM:
 ```
/*
Program to implement a Getter and Setter using Java
Developed by: Jayasree R
RegisterNumber: 212223040074 
*/
```
```
import java.util.*;
public class SetAndGet {
private String a;
private String b;

public void getadd() {
    int a1=Integer.parseInt(a);
    int b1=Integer.parseInt(b);
	System.out.print("Sum is " + (a1+b1)); 
	
}
public void setadd(String a,String b) {
 this.a =a;
 this.b=b;
}

public static void main(String args[]){
 Scanner sc=new Scanner(System.in);
 SetAndGet obj = new SetAndGet();
 String str=sc.nextLine();
 String str1=sc.nextLine();
 
 obj.setadd(str,str1);
 
 obj.getadd();
}
}
```





## OUTPUT:
![image](https://github.com/user-attachments/assets/031a8455-6d32-4841-821c-04e2b499b489)



## RESULT:
Thus the java program to print the sum of two number using getter and setter method was executed successfully.






