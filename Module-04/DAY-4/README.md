# Ex.No:4(D) FINAL & STATIC IN JAVA

## AIM:
   To create a Java program to perform final & static keyword for below situation Employee object contains member 'Emp_Id'. It contains object named name, which contains its own informations such as Fname, Mname, Lname.
 
## ALGORITHM :
1.	Start the Program.
2.	Define class `Name`:
-	a) Declare three `String` variables: `Fname`, `Mname`, and `Lname`
-	b) Define method `dispName(String fn, String mn, String ln)`:
-	i) Print the full name using the passed parameters `fn`, `mn`, and `ln`
3.	Define class `Employee`:
-	a) Declare an integer variable `Emp_Id`
-	b) Create an instance of `Name` called `obj`
-	c) Define method `disp(int id)`:
-	i) Print the employee ID
-	ii) Create a new `Name` object and call `dispName("B", "Leo", "John")` to display the name
4.	Define `Main` class with `main` method:
-	a) Create an `Employee` object `emp`
-	b) Call `emp.disp(101)` to display the employee details
5.	End






## PROGRAM:
 ```
/*
Program to implement a final & Static using Java
Developed by: Jayasree R
RegisterNumber:  212223040074
*/
```
```
public class StaticVariableExample 
{
    public static void main(String[] args) 
    {
        Employee emp1 = new Employee("E101", "Emp1", "Accountant");
        Employee emp2 = new Employee("E102", "Emp2", "Manager");
        Employee emp3 = new Employee("E103", "Emp3", "Programer");
        Employee emp4 = new Employee("E104", "Emp4", "Receptionist");
        emp1.display();
        emp2.display();
        emp3.display();
        emp4.display();
    }
}
class Employee 
{
    String empNo;
    String name;
    String designation;
    static String companyName = "Green Tech";
    Employee(String empNo, String name, String designation)
    {
        this.empNo = empNo;
        this.name = name;
        this.designation = designation;
    }
    void display() 
    {
        System.out.println("Empno is " + empNo + " Name is " + name + " Designation is " + designation + " Company Name is " + companyName);
    }
}
```







## OUTPUT:

![image](https://github.com/user-attachments/assets/cb16fa9d-18de-4b4b-9bf1-b48e6b1000e7)


## RESULT:
Thus, the java program to perform final & static keyword was executed successfully.
