# Ex.No:1(E) STRINGS AND MATH FUNCTION

## QUESTION:
Write a Java program to demonstrate the use of Strings and Math functions.

## AIM:
To write and execute a Java program to perform basic String operations and mathematical functions using Java.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Create a String variable and assign a string value.
4.	Display the length of the string.
5.	Convert the string to uppercase and display it.
6.	Use Math functions such as Math.sqrt(), Math.pow(), and Math.max().
7.	Display the results of the mathematical operations.
8.	Stop the program.

## PROGRAM:
 ```
/*
Program to implement a Strings and Math Function using Java
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

        System.out.print("Enter a string: ");
        String str = sc.nextLine();

        System.out.println("String: " + str);
        System.out.println("Length of string: " + str.length());
        System.out.println("Uppercase: " + str.toUpperCase());
        System.out.println("Lowercase: " + str.toLowerCase());

        System.out.println("\nMath Functions:");
        System.out.println("Square root of 25: " + Math.sqrt(25));
        System.out.println("2 raised to power 3: " + Math.pow(2, 3));
        System.out.println("Maximum of 10 and 20: " + Math.max(10, 20));

        sc.close();
    }
}
```

## OUTPUT:
```
Enter a string: Java

String: Java
Length of string: 4
Uppercase: JAVA
Lowercase: java

Math Functions:
Square root of 25: 5.0
2 raised to power 3: 8.0
Maximum of 10 and 20: 20
```


## RESULT:
Thus, the Java program was successfully written and executed to demonstrate String operations and Math functions in Java.
