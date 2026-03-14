# Ex.No:2(E) ACCESS MODIFIERS

## QUESTION:

## AIM:

To create an Employee class where the display() method returns the current object using this, and demonstrate calling display().printName() from another method.

## ALGORITHM :

1.Create a class Employee with a variable name.

2.Define methods setName(), display() (returns this), printName(), and show().

3.In the main() method, create a Scanner object to read the employee name.

4.Create an Employee object and set the name using setName().

5.Call display().printName() and show() to demonstrate method chaining and end the program.


## PROGRAM:
 ```
/*
Program to implement a Access Modifiers using Java
Developed by : K.Mohamed Althaf
Register Number : 212224240089
*/
```

## SOURCE CODE:

```
import java.util.*;

class Employee {
    String name;

    void setName(String name) {
        this.name = name;  
    }

    Employee display() {
        return this;  
    }

    void printName() {
        System.out.println("Employee Name: " + name);
    }
}

class prog {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        String inputName = scanner.nextLine();

        Employee emp = new Employee();
        emp.setName(inputName);
        emp.display().printName();  
    }
}
```


## OUTPUT:

<img width="686" height="326" alt="image" src="https://github.com/user-attachments/assets/954fafa4-a638-4044-b666-3322017194cd" />


## RESULT:

Program executed successfully.








