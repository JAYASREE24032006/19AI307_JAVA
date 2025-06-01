# Ex.No:7(E)  POLYMORPHISM

## AIM:
To implement method overloading in Java to Write a Java program using copy constructor to print the area of rectangle [l=5,w=6]" — is the one that belongs to the concept of polymorphism. demonstrating compile-time polymorphism
## ALGORITHM :
1.Start

2.Create a class Rectangle with two integer variables: length and width.

3.Define a parameterized constructor that accepts values for length and width.

4.Define a copy constructor that accepts an object of Rectangle and copies its values.

5.Create a method getArea() that returns the area (length * width).

6.In the main method:

7.Create the first Rectangle object using the parameterized constructor.

8.Print the area of the first rectangle.

9.Create the second Rectangle object using the copy constructor.

10.Print the area of the second rectangle.

11.End

## PROGRAM:
 ```
/*
Program to implement a Method Overloading in Java
Developed by: Jayasree R
RegisterNumber:  212223040074
*/
```

```
class Rectangle {
    int length, width;

    // Parameterized constructor
    Rectangle(int l, int w) {
        length = l;
        width = w;
    }

    // Copy constructor
    Rectangle(Rectangle r) {
        length = r.length;
        width = r.width;
    }

    // Method to calculate area
    int getArea() {
        return length * width;
    }
}

public class Main {
    public static void main(String[] args) {
        Rectangle rect1 = new Rectangle(5, 6);
        System.out.println("Area  of First Rectangle : " + rect1.getArea());

        Rectangle rect2 = new Rectangle(rect1);
        System.out.println("Area of First Second Rectangle : " + rect2.getArea());
    }
}

```





## OUTPUT:


![image](https://github.com/user-attachments/assets/390fc7b0-a87e-48cd-90e7-415861bc36b3)


## RESULT:

Thus the  java program successfully demonstrates method overloading, showing compile-time polymorphism by calculating the sum of two and three numbers using methods with the same name but different parameter lists..


