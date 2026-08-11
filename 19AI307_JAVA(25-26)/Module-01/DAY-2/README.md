# Ex.No:1(B) CONDITIONAL STATEMENT

## QUESTION:
Write a Java program to demonstrate the use of conditional statements using if-else.

## AIM:
To write and execute a Java program using conditional statements to check whether a given number is positive, negative, or zero.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Create a Scanner object to get input from the user.
4.	Read an integer from the user.
5.	If the number is greater than zero, display "Positive number".
6.	Else if the number is less than zero, display "Negative number".
7.	Otherwise, display "Zero".
8.	Stop the program.

## PROGRAM:
 ```
/*
Program to implement a conditional statement using Java
Developed by: Srinidhi R
RegisterNumber: 212224020052
*/
```

## SOURCE CODE:
```
import java.util.Scanner;

public class Sourcecode {
    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        System.out.print("Enter a number: ");
        int n = sc.nextInt();

        if (n > 0) {
            System.out.println("Positive number");
        } 
        else if (n < 0) {
            System.out.println("Negative number");
        } 
        else {
            System.out.println("Zero");
        }

        sc.close();
    }
}
```

## OUTPUT:
```
Enter a number: 25
Positive number
```

## RESULT:
Thus, the Java program was successfully written and executed to demonstrate the use of conditional statements using if-else.
