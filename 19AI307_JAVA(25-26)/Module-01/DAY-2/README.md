# Ex.No:1(B) CONDITIONAL STATEMENT

## QUESTION:


## AIM:

A dragon wakes based on temperature:

If temperature < 0, it hibernates.

If 0 ≤ temp ≤ 20, it snoozes.

If 21 ≤ temp ≤ 35, it wakes.

If temp > 35, it gets angry.

Write a java program to get the user input for temperature and display appropriate output from one of the following.

Hibernating
Snoozing
Awake
Angry

## ALGORITHM :

1.Start the program.

2.Import java.util and create a Scanner object to read an integer input.

3.Read the value i from the user.

4.Use if-else conditions to check the range of i and determine the state.

5.Print Hibernating, Snoozing, Awake, or Angry based on the value and end the program.


## PROGRAM:
 ```
/*
Program to implement a conditional statement using Java
Developed by: K.Mohamed Althaf
RegisterNumber:  212224240089
*/
```

## SOURCE CODE:

```
import java.util.*;
public class seo
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int i=sc.nextInt();
        if(i<0)
        {
            System.out.println("Hibernating");
        }
        else if(i>=0 && i<=20)
        {
            System.out.println("Snoozing");
        }
        else if(i>=21 && i<=35)
        {
            System.out.println("Awake");
        }
        else
        {
            System.out.println("Angry");
        }
    }
}
```

## OUTPUT:

<img width="1233" height="389" alt="image" src="https://github.com/user-attachments/assets/d8a0ae6b-b6e1-49e3-b24b-0512ed2fb4e0" />


## RESULT:

Program executed successfully.
