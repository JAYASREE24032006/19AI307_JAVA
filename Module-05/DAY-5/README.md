# Ex.No:5(E) HAS-A RELATIONSHIP
## AIM:
To implement a  Java Program to Find the Largest or Max Number in Array using has - a relationship.
## ALGORITHM :
1.	Start the program.
2.	Create a class ArrayData:
a.	Declare an integer array and a variable for size.
b.	Create a method to read array elements from the user.
3.	Create another class ArrayOperation:
a.	Create a method findMax() that accepts an ArrayData object.
b.	Loop through the array and find the largest element.
4.	In the main() method of a class Main:
a.	Create an object of ArrayData and read the input.
b.	Create an object of ArrayOperation and call findMax() by passing the ArrayData object.
5.	Display the largest number.
6.	End the program.



## PROGRAM:
 ```
/*
Program to implement a HAS-A RelationShip
Developed by: Jayasree R
RegisterNumber:  212223040074
*/
```
```
import java.util.Scanner;
class ArrayUtility
{
    private int[] numbers;
    public ArrayUtility(int[] numbers) 
    {
        this.numbers = numbers;
    }
    public int findMax() 
    {
        int max = numbers[0];
        for (int i = 1; i < numbers.length; i++) 
        {
            if (numbers[i] > max) 
            {
                max = numbers[i];
            }
        }
        return max;
    }
}
public class Main 
{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
        int size = sc.nextInt();
        int[] arr = new int[size];
        for (int i = 0; i < size; i++) 
        {
            arr[i] = sc.nextInt();
        }
        ArrayUtility utility = new ArrayUtility(arr);
        int max = utility.findMax();
        System.out.println("Largest element = " + max);
        sc.close();
    }
}

```





## OUTPUT:

![image](https://github.com/user-attachments/assets/54a1e8ad-e955-4858-8458-7a31efc4f8cc)


## RESULT:
Thus the java program to Find the Largest or Max Number in Array using has - a relationship was executed successfully. 

