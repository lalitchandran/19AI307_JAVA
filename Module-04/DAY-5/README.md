# Ex.No:4(E)  PARAMETERIZED CONSTRUCTOR
## AIM:
To write a parameterized constructor in the Employee class that initializes name and designation, and then call getter methods in the main() method of another class (Sample) to display the values.

## ALGORITHM :

	1.	Start the program.

2.	Define a class Employee:
   
    a.	  Declare two private string variables: name and designation.
  	
4.	Create a parameterized constructor in Employee:
   
5.	Accept two parameters: name and designation.
   
6.	Assign the parameters to the class fields.
   
7.	Define two getter methods in the Employee class:
     a.	getName() – returns the value of name.
     b.	getDesg() – returns the value of designation.
  	
8.	Create another class Sample with the main method.
   
9.	Inside the main method:
     a.	Create an object of Employee using the constructor and pass "John" and "Asst.Manager" as arguments.
     b.	Call getName() and store the result in a variable empName.
     c.	Call getDesg() and store the result in a variable empDesg.
  
10.	Print the values of empName and empDesg.
    
11.	End the program


## PROGRAM:
 ```
/*
Program to implement a Parameterized Constructor Using Java
Developed by: S LALIT CHANDRAN
RegisterNumber:  212223240077
*/
```

## Sourcecode.java:
```
public class Employee {
    // Instance variables for employee details
    private String name;
    private int age;
    private String designation;

    // Default constructor to initialize the employee details
    public Employee() {
        // Assign default values
        this.name = "Robert";
        this.age = 35;
        this.designation = "Senior Developer";
    }

    // Instance method to display employee details
    public void displayDetails() {
        System.out.println("Name is:" + name);
        System.out.println("Age is:" + age);
        System.out.println("Designation is:" + designation);
    }

    public static void main(String[] args) {
        // Create an object of the Employee class using the default constructor
        Employee employee = new Employee();

        // Call the displayDetails method to print employee information
        employee.displayDetails();
    }
}
```






## OUTPUT:

![image](https://github.com/user-attachments/assets/f66b4b8c-e28a-44c7-ac98-8433c36de919)


## RESULT:
Thus, the  java program was successfully demonstrates the use of a parameterized constructor to initialize class fields.

 


