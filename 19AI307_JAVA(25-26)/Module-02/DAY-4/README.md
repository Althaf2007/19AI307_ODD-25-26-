# Ex.No:2(D) VARIABLE SCOPE AND CONSTRUCTOR

## QUESTION:

To write a Java program that initializes object variables using a constructor and overrides the toString() method to display object details in a readable format.

## AIM:

To demonstrate the use of a constructor for initializing object variables and overriding the toString() method to display object details.

## ALGORITHM :

1.Define a class Student with instance variables name and age.

2.Create a parameterized constructor to initialize these variables.

3.Override the toString() method to return the student details in a formatted string.

4.In the main() method, read the name and age and create a Student object using the constructor.

5.Print the object to display the student details and end the program.


## PROGRAM:
 ```
/*
Program to implement a Variable scope and Constructor using Java
Developed by : K.Mohamed Althaf
Register Number : 212224240089
*/
```

## SOURCE CODE:

```
import java.util.*;

class Student {
    String name;
    int age;

    public Student(String name, int age) {
        this.name = name;
        this.age = age;
    }

    @Override
    public String toString() {
        return "Student{name='" + name + "', age=" + age + "}";
    }
}

public class StudentDemo {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        String name = scanner.nextLine();
        int age = scanner.nextInt();

        Student student = new Student(name, age);
        System.out.println(student.toString());
    }
}
```




## OUTPUT:

<img width="896" height="395" alt="image" src="https://github.com/user-attachments/assets/0b280b01-a09a-4749-b733-41411f01b00a" />


## RESULT:

The object details are successfully displayed in a formatted and readable manner.








