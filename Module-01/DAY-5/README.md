# Ex.No:1(E)  STATIC VARIABLE

## AIM:
To write a Java program to print student details (name and age), where age is the same for all students. Use a static variable to represent the age and demonstrate its use in accessing a shared value across all class objects

## ALGORITHM :
1.	Start the program.
2.	Create a class named Student.
3.	Declare a static variable age in the Student class.
4.	Declare an instance variable name.
5.	Create a constructor to initialize the student's name.
6.	Define a method displayDetails() to print the student's name and age.
7.	In the main method:
I.	Assign a value to the static variable age.
II.	Create multiple Student objects with different names.
III.	Call the displayDetails() method for each student.
8.	End the program.



## PROGRAM:
 ```
/*
Program to implement a Static Variable using Java
Developed by: S LALIT CHANDRAN
RegisterNumber:  212223240077
*/
```

## Sourcecode.java:

```
import java.util.*;
public class Main
{
    static int age=18;
    String name;
	public static void main(String[] args) {
	Scanner sc=new Scanner(System.in);
	Main obj1=new Main();
	Main obj2=new Main();
	obj1.name=sc.next();
	obj2.name=sc.next();
	System.out.println("Student name: "+obj1.name+"Age: "+age);
	System.out.println("Student name: "+obj2.name+"Age: "+age);
	}
}
```





## OUTPUT:
![image](https://github.com/user-attachments/assets/614a6fa8-d9b8-4ba5-a3f2-4af076772380)



## RESULT:
Thus, the Java program for the concept of using a static variable for shared data was correctly implemented and verified successfully. 

