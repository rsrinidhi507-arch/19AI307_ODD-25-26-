# Ex.No:1(A) INTRODUCTION TO JAVA PROGRAMMING, DATA TYPES, VARIABLES AND OPERATORS

## QUESTION:
Write a Java program to demonstrate the use of different data types, variables, and operators.


## AIM:
To write and execute a Java program that demonstrates the use of data types, variables, and various operators in Java.


## ALGORITHM :
1.Start the program.

2.Declare variables using different data types such as int, float, double, char, and boolean.

3.Assign suitable values to the variables.

4.Perform arithmetic operations such as addition, subtraction, multiplication, division, and modulus.

5.Perform relational and logical operations.

6.Display the values and results of the operations.

7.Stop the program.



## PROGRAM:
 ```
/*
Program to implement variables and Operators using Java
Developed by:
RegisterNumber:
*/

```

## Sourcecode.java:

```

public class Sourcecode {
    public static void main(String[] args) {

        // Declaration of variables using different data types
        int a = 20;
        int b = 10;
        float x = 5.5f;
        double y = 10.25;
        char grade = 'A';
        boolean status = true;

        // Displaying variables
        System.out.println("Integer value: " + a);
        System.out.println("Float value: " + x);
        System.out.println("Double value: " + y);
        System.out.println("Character value: " + grade);
        System.out.println("Boolean value: " + status);

        // Arithmetic operators
        System.out.println("\nArithmetic Operators:");
        System.out.println("Addition: " + (a + b));
        System.out.println("Subtraction: " + (a - b));
        System.out.println("Multiplication: " + (a * b));
        System.out.println("Division: " + (a / b));
        System.out.println("Modulus: " + (a % b));

        // Relational operators
        System.out.println("\nRelational Operators:");
        System.out.println("a > b : " + (a > b));
        System.out.println("a < b : " + (a < b));
        System.out.println("a == b : " + (a == b));

        // Logical operators
        System.out.println("\nLogical Operators:");
        System.out.println("(a > b) && status : " + ((a > b) && status));
        System.out.println("(a < b) || status : " + ((a < b) || status));
        System.out.println("!(status) : " + (!status));
    }
}
```

## OUTPUT:
```
Integer value: 20
Float value: 5.5
Double value: 10.25
Character value: A
Boolean value: true

Arithmetic Operators:
Addition: 30
Subtraction: 10
Multiplication: 200
Division: 2
Modulus: 0

Relational Operators:
a > b : true
a < b : false
a == b : false

Logical Operators:
(a > b) && status : true
(a < b) || status : true
!(status) : false
```

## RESULT:

Thus, the Java program was successfully written and executed to demonstrate data types, variables, arithmetic operators, relational operators, and logical operators.
