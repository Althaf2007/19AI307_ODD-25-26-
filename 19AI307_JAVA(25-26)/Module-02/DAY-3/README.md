# Ex.No:2(C) ACCESS SPECIFIERS

## QUESTION:

## AIM:

To write a Java program that defines a class BankAccount with private attributes accountNumber and balance,and provides public getter and setter methods to access and modify these values.

## ALGORITHM :

1.Define a class BankAccount with private variables accountNumber and balance.

2.Create public getter and setter methods for both variables.

3.In the main() method, create a Scanner object to read user input.

4.Create a BankAccount object and store the input values using setter methods.

5.Retrieve and display the values using getter methods and end the program.





## PROGRAM:
 ```
/*
Program to implement a Access Specifiers using Java
Developed by : K.Mohamed Althaf
Register Number : 212224240089
*/
```

## SOURCE CODE:

```
import java.util.*;

class BankAccount {
   
    private String accountNumber;
    private double balance;

    
    public String getAccountNumber() {
        return accountNumber;
    }
    public void setAccountNumber(String accountNumber) {
        this.accountNumber = accountNumber;
    }

   
    public double getBalance() {
        return balance;
    }
    public void setBalance(double balance) {
        this.balance = balance;
    }
}

public class prog {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        BankAccount account = new BankAccount();

        String accNo = sc.nextLine();
        double bal = sc.nextDouble();

        account.setAccountNumber(accNo);
        account.setBalance(bal);

        System.out.println("Account Number: " + account.getAccountNumber());
        System.out.println("Balance: " + account.getBalance());
    }
}
```

## OUTPUT:

<img width="826" height="465" alt="image" src="https://github.com/user-attachments/assets/972c4fcf-d9d0-43f8-bc30-518764a4d55e" />



## RESULT:

Program executed successfully.





