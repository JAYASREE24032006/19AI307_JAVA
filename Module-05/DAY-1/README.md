# Ex.No:5(A)  DATA HIDING AND ENCAPSULATION
## AIM:
To Create a java program to display name and location of the employee and use the encapsulation concepts

## ALGORITHM :
1.  Start the program
2.	Define class `Employee`:
-	a) Declare two private `String` variables: `name1` and `name2`
-	b) Define `setname(String n1)` method to set `name1` to `n1`
-	c) Define `setname2(String n2)` method to set `name2` to `n2`
-	d) Define `get1()` method to return `name1`
-	e) Define `get2()` method to return `name2`
3.	Define `Main` class with `main` method:
-	a) Create `Scanner` object `sc` for input
-	b) Read `name1` and `name2` from user input
-	c) Create ` Employee ` object `hl`
-	d) Use `hl.setname(name1)` and `hl.setname2(name2)` to set the names
-	e) Print the values of `hl.get1()` and `hl.get2()`
4.	End





## PROGRAM:
 ```
/*
Program to implement a Data Hiding & Encapsulation using Java
Developed by: Jayasree R
RegisterNumber:  212223040074
*/
```
```
import java.util.*;
class vehicle 
{
    private String Name;
    private String location;
    public String getName()
    {
        return Name;
    }
    public void setName(String Name)
    {
        this.Name = Name;
    }
    public String getLocation() 
    {
        return location;
    }
    public void setLocation(String location)
    {
        this.location = location;
    }
}
public class EmployeMain 
{
    public static void main(String[] args) 
    {
        Scanner sc=new Scanner(System.in);
        vehicle employee = new vehicle();
        employee.setName(sc.nextLine());
        employee.setLocation(sc.nextLine());
        System.out.println(employee.getName());
        System.out.println(employee.getLocation());
 }
}
```



## OUTPUT:
![image](https://github.com/user-attachments/assets/4e0fb984-5b58-4491-941e-823f4c2a2d4f)



## RESULT:
Thus , the  java program to display name and location of the employee and use the encapsulation concepts executed successfully.
