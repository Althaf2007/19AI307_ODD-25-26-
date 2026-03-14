# Ex.No:2(A) CLASS AND OBJECT

## QUESTION:

To define a class Car with attributes brand, color, and year.Create two objects of the class.Assign values to their attributes and print the details of both cars.

## AIM:

To define a class Car with attributes brand, color, and year, create two objects of the class, assign values to them, and display their details.

## ALGORITHM :

1.Define a class Car with data members brand, color, and year.

2.In the main() method, create a Scanner object to read user input.

3.Create the first object car1 and read its brand, color, and year.

4.Create the second object car2 and read its brand, color, and year.

5.Call printDetails() for both objects to display the car information.


## PROGRAM:
 ```
/*
Program to implement a Class and Objects using Java
Developed by : K.Mohamed Althaf
Register Number : 212224240089
*/
```

## SOURCE CODE:

```
import java.util.*;

class Car {
    String brand;
    String color;
    int year;

    void printDetails() {
        System.out.println("Brand: " + brand);
        System.out.println("Color: " + color);
        System.out.println("Year: " + year);
    }
}

class prog {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        
        Car car1 = new Car();
        car1.brand = scanner.nextLine();
        car1.color = scanner.nextLine();
        car1.year = scanner.nextInt();
        scanner.nextLine();

        
        Car car2 = new Car();
        car2.brand = scanner.nextLine();
        car2.color = scanner.nextLine();
        car2.year = scanner.nextInt();

        car1.printDetails();
        car2.printDetails();
    }
}
```


## OUTPUT:

<img width="597" height="685" alt="image" src="https://github.com/user-attachments/assets/05ebe553-f279-4f17-b125-675b4afd47bd" />


## RESULT:

The details of both car objects are displayed successfully.

