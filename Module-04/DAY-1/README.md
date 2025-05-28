# Ex.No:4(A)  JAVA CONSTRUCTOR
## AIM:
To create a Java program using constructor to print the circumference of rectangle.[l=5,w=6]

## ALGORITHM :
1.  1.	Start the Program.
2.	Define a class `circum`
3.	Inside the class, define two integer variables `l` and `w` with values 5 and 6, respectively
4.	Create a constructor `circum()`:
-	a) Calculate the `circumference` as `2 * (l + w)`
-	b) Print the `circumference` twice with different labels ("Area of First Rectangle" and "Area of Second Rectangle")
5.	In `main`, create an object `sc` of the `circum` class
6.	End





## PROGRAM:
 ```
/*
Program to implement a Constructor using Java
Developed by: Jayasree R
RegisterNumber:  212223040074
*/
```
```
class circum {
    int l = 5;
    int w = 6;

    // Constructor
    circum() {
        int circumference = 2 * (l + w);
        System.out.println("Circumference of First Rectangle: " + circumference);
        System.out.println("Circumference of Second Rectangle: " + circumference);
    }

    public static void main(String[] args) {
        // Create object which invokes the constructor
        circum sc = new circum();
    }
}
```





## OUTPUT:
![image](https://github.com/user-attachments/assets/84845cba-0fda-4901-b589-4faf0ff6f9ab)



## RESULT:
Thus the Java program using constructor to print the circumference of rectangle was executed successfully.
