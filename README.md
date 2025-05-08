# Cos261-Tests
Cos261 tests answers 

Basic & Syntax
1. Write a Java program to print "Hello, World".
   ANSWER
package cos261test;
public class Cos261Test {
    public static void main(String[] args) {
        System.out.println("Hello, World");
    }
}

run:
Hello, World
BUILD SUCCESSFUL (total time: 0 seconds)

![Screenshot (11)](https://github.com/user-attachments/assets/52c7426a-8dea-4a84-85e9-73ccc67dd274)

4. Write a Java program to add two numbers entered by the user.
   ANSWER
package cos261test;
import java.util.Scanner;

public class Cos261Test {
    public static void main(String[] args) {
        int num1, num2;
        int sum;
        Scanner input = new Scanner(System.in);
        System.out.print("Enter first number : ");
        num1 = input.nextInt();
        System.out.print("Enter second number : ");
        num2 = input.nextInt();
        sum = num1 + num2;
        System.out.println("The sum of the two numbers are : " + sum);
    }
}

run:
Enter first number : 3
Enter second number : 4
The sum of the two numbers are : 7
BUILD SUCCESSFUL (total time: 3 seconds)

![Screenshot (12)](https://github.com/user-attachments/assets/2bb86b21-fd22-4767-baa0-16c0ebb7a2ff)
