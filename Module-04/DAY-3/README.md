# Ex.No:4(C)    CONSTRUCTOR CHAINING(SUPER KEYWORD)

## AIM:
To Create a Java program to implement super keyword in constructor.

## ALGORITHM :
1.  Start the Program.
2.	Define class `College`:
-	a) Define method `display()` that prints "I am a Vehicle"
3.	Define class `Student` that extends `College`:
-	a) Override method `display()` to print "I am a Car"
-	b) Define method `print()`:
-	i) Call `super.display()` to invoke `display()` from `College` class
-	ii) Call `this.display()` to invoke `display()` from `Student` class
4.	Define `Main` class with `main` method:
-	a) Create a `Student` object `sc`
-	b) Call `sc.print()` to execute the `print()` method
5.	End







## PROGRAM:
 ```
/*
Program to implement a Constructor Chaining using Java
Developed by: Jayasree R
RegisterNumber:  212223040074
*/
```
```
// College.java
class College {
    College() {
        System.out.println("College Constructor Called");
    }

    void display() {
        System.out.println("I am a Vehicle");
    }
}

// Student.java
class Student extends College {
    Student() {
        super(); // Calls the constructor of College
        System.out.println("Student Constructor Called");
    }

    void display() {
        System.out.println("I am a Car");
    }

    void print() {
        super.display(); // Calls display() from College
        this.display();  // Calls display() from Student
    }
}

// Main.java
public class Main {
    public static void main(String[] args) {
        Student sc = new Student();
        sc.print();
    }
}
```




## OUTPUT:
```
College Constructor Called
Student Constructor Called
I am a Vehicle
I am a Car
```

## RESULT:
Thus the java program for constructor chaining was executed successfully.




