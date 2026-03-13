# Ex.No:1(D) ARRAYS

## QUESTION:


## AIM:

Write a Java program to sort an array in ascending order

## ALGORITHM :
1.Start the program.

2.Import java.util and create a Scanner object to read input.

3.Read the size n and store n elements in an array.

4.Use Arrays.sort() to sort the array elements in ascending order.

5.Print the sorted array elements and end the program.


## PROGRAM:
 ```
/*
Program to implement a Array concept using Java
Developed by: K.Mohamed Althaf
RegisterNumber:  212224240089
*/
```

## SOURCE CODE:

```
import java.util.*;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int[] arr = new int[n];
        for (int i = 0; i < n; i++) {
            arr[i] = sc.nextInt();
        }
        Arrays.sort(arr);
        for (int i = 0; i < n; i++) {
            System.out.print(arr[i] + " ");
        }
    }
}
```

## OUTPUT:

<img width="1234" height="632" alt="image" src="https://github.com/user-attachments/assets/364f1458-dcc6-4fbb-9c09-b2b101ecce6b" />


## RESULT:

Program executed successfully
