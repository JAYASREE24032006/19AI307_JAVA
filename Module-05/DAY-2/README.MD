# Ex.No:5(B) TIGHTLY ENCAPSULATED CLASS

## AIM:
To Create a java program to display the value of volume of cylinder get the radius and height value as input and use tightly encapsulated class.

## ALGORITHM :
1.	Start the program.
2.	Define `Cylinder` class:
-	a) Private variables `radius` and `height`
-	b) `setRadius(int r)` and `setHeight(int h)` methods to set values
-	c) `getVolume()` method:
- i) Calculate and print `volume = pi * radius * radius * height`
3.	In `Main` class `main` method:
-	a) Use `Scanner` to read `radius` and `height`
-	b) Create `Cylinder` object, set values, and call `getVolume()`
4.	End









## PROGRAM:
 ```
/*
Program to implement a tightly encapsulated class using Java
Developed by: Jayasree R
RegisterNumber:  212223040074
*/
```
```
import java.util.*;
public class SetAndGet {
private double r;
private double h;


public void getvol() {
     double  volume=((22*r*r*h)/7);
     System.out.println("volume of Cylinder is: " +volume);
	
}
public void setvol(double r,double h) {
 this.r =r;
 this.h=h;
 
}

public static void main(String args[]){
 Scanner sc=new Scanner(System.in);
 SetAndGet obj = new SetAndGet();
 Double r=sc.nextDouble();
 Double h=sc.nextDouble();
 obj.setvol(r,h);
 
 obj.getvol();
}
}

```


## OUTPUT:
```
5.2
8.5
volume of Cylinder is: 722.3542857142857
```

## RESULT:
Thus a java program to display the value of volume of cylinder get the radius and height value as input and use tightly encapsulated class was executed successfully.



