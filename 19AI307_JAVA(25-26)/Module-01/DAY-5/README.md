# Ex.No:1(E) STRINGS AND MATH FUNCTION

## QUESTION:


## AIM:

Write a Java program to concatenate two strings.

## ALGORITHM :

1.Start the program.

2.Import java.util and create a Scanner object to read input strings.

3.Read two strings s1 and s2 from the user.

4.Use the concat() method to join s1 and s2.

5.Display the concatenated string and end the program.




## PROGRAM:
 ```
/*
Program to implement a Strings and Math Function using Java
Developed by: K.Mohamed Althaf
RegisterNumber:  212224240089
*/
```

## SOURCE CODE:

```
import java.util.*;

public class seo {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        String s1 = sc.nextLine();
        String s2 = sc.nextLine();

        String con = s1.concat(s2);

        System.out.println("Concatenated string: " + con);
    }
}
```


## OUTPUT:

<img width="1238" height="413" alt="image" src="https://github.com/user-attachments/assets/bebb8a4a-e6d9-44ca-aa22-bb780f139730" />


## RESULT:

Program executed successfully
