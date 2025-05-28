# Ex.No:4(B) INTRODUCTION TO JAVA INHERITANCE

## AIM:
To create  a Java program to Java Program to implement following IS-A relationship.

## ALGORITHM :
1.Start the program.

2.Create a class named College.

3.Define a string variable collegeName and assign a value.

4.Create a class named Student that extends College.

5.Declare instance variables: rollNo (int), name (String).

6.Define a method get() to input roll number and name.

7.Define a method display() to print collegeName, rollNo, and name.

8.In the main() method:

9.Create an object of Student.

10.Call the get() method to input data.

11.Call the display() method to output the data.

12.End the program.







## PROGRAM:
 ```
/*
Program to implement a Inheritance using Java
Developed by: Jayasree R
RegisterNumber:  212223040074
*/
```

```

class College {
    // Base class
    String collegeName = "ABC College";
}

class Student extends College {
    // Subclass
    int rollNo;
    String name;

    void get(int r, String n) {
        rollNo = r;
        name = n;
    }

    void display() {
        System.out.println("College Name: " + collegeName);
        System.out.println("Student Roll No: " + rollNo);
        System.out.println("Student Name: " + name);
    }

    public static void main(String[] args) {
        Student s1 = new Student();
        s1.get(101, "Jayasee");
        s1.display();
    }
}

```



## OUTPUT:

```
Input
1
Student1
Output : RollNo: 1Name: Student1
```


## RESULT:
Thus the Java program to implement following IS-A relationship.was  executed successfully.

