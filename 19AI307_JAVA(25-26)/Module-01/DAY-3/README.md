# Ex.No:1(C) LOOPING STATEMENT

## QUESTION:


## AIM:

Reversing a number means rearranging its digits in the opposite order. 

For example:

.The reverse of 1234 is 4321

.The reverse of 9870 is 789 (since leading zeros in the reversed number are not shown)

Write a Java program that takes an integer input from the user and then reverses its digits using a while loop.

.The program should repeatedly extract the last digit of the number using the modulus operator (%) and then build the reversed number.

.The loop should continue until the number becomes 0.

.Finally, display the reversed number as output.

## ALGORITHM :

1.Start the program.

2.Import java.util and create a Scanner object to read an integer input.

3.Read the number and initialize reversed as 0.

4.Use a while loop to extract digits using % 10 and build the reversed number.

5.Print the reversed number and end the program.




## PROGRAM:
 ```
/*
Program to implement a Looping Statement using Java
Developed by: K.Mohamed Althaf
RegisterNumber:  212224240089
*/
```

## SOURCE CODE:

```
import java.util.*;

public class Reverse {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int number = sc.nextInt();
        int reversed = 0;
        while (number != 0) {
            int digit = number % 10;        
            reversed = reversed * 10 + digit; 
            number = number / 10;       
        }
        System.out.println("Reversed number: " + reversed);
    }
}
```


## OUTPUT:

<img width="1280" height="353" alt="image" src="https://github.com/user-attachments/assets/8d77bd0a-0ddb-407e-b183-2ea918aac801" />


## RESULT:

Program executed successfully.
