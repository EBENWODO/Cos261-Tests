![image](https://github.com/user-attachments/assets/1759e07c-0dae-41d9-be9f-91e9656f0b97)# Cos261-Tests
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

Control Structures
6. Write a program to check if a number is even or odd
   ANSWER
package cos261test;
import java.util.Scanner;

public class Cos261Test {
    public static void main(String[] args) {
        int numb;
        Scanner input = new Scanner(System.in);
        System.out.print("Enter number : ");
        numb = input.nextInt();
        if (numb % 2 == 0) {
        System.out.println("The number is even");
        }else{
        System.out.println("The number is odd");
        }
    }
}

run:
Enter number : 64
The number is even
BUILD SUCCESSFUL (total time: 4 seconds)

![Screenshot (13)](https://github.com/user-attachments/assets/f0f8583c-c962-4e07-bd3a-2a5e00161325)

7. Write a program to find the largest among three numbers.
   ANSWER
package cos261test;
import java.util.Scanner;

public class Cos261Test {
    public static void main(String[] args) {
      int num1,num2,num3;  
      Scanner input = new Scanner (System.in);
      System.out.print("Enter first number : ");
      num1 = input.nextInt();
      System.out.print("Enter second number : ");
      num2 = input.nextInt();
      System.out.print("Enter third number : ");
      num3 = input.nextInt();
        if (num1 >= num2 && num1 >= num3) {
            System.out.print("number " + num1 + " is the largest number");
        }else if (num2 >= num1 && num2 >= num3) {
            System.out.print("number " + num2 + " is the largest number");
        }else {System.out.println("number " + num3 + " is the largest number");
        }
    }
}

run:
Enter first number : 1
Enter second number : 2
Enter third number : 3
number 3 is the largest number
BUILD SUCCESSFUL (total time: 5 seconds)

![image](https://github.com/user-attachments/assets/1d12e83d-974b-4551-a6d7-ac795fefa803)







