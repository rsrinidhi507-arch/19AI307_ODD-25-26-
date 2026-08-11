# Ex.No:1(D) ARRAYS

## QUESTION:
Write a Java program to demonstrate the implementation of a one-dimensional array.

## AIM:
To write and execute a Java program to store and display elements using an array.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Create a Scanner object to get input from the user.
4.	Declare an integer array of size 5.
5.	Read 5 elements from the user and store them in the array.
6.	Use a for loop to access each element of the array.
7.	Display all the elements of the array.
8.	Stop the program.


## PROGRAM:
 ```
/*
Program to implement a Array concept using Java
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

        int[] arr = new int[5];

        System.out.println("Enter 5 elements:");

        for (int i = 0; i < 5; i++) {
            arr[i] = sc.nextInt();
        }

        System.out.println("Array elements are:");

        for (int i = 0; i < 5; i++) {
            System.out.println(arr[i]);
        }

        sc.close();
    }
}
```

## OUTPUT:
```
Enter 5 elements:
10
20
30
40
50

Array elements are:
10
20
30
40
50
```

## RESULT:
Thus, the Java program was successfully written and executed to demonstrate the creation, storage, and retrieval of elements using a one-dimensional array.
