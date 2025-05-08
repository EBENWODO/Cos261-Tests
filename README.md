#Cos261 Tests
Cos261 tests answers 

Basic & Syntax
1. Write a Java program to print "Hello, World".
   ANSWER
package cos261test;

public class Cos261Test {
    public static void main(String[] args) {
    //printing out the hello world
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
    //initializing variables
        int num1, num2;
        int sum;
        //users input
        Scanner input = new Scanner(System.in);
        System.out.print("Enter first number : ");
        num1 = input.nextInt();
        System.out.print("Enter second number : ");
        num2 = input.nextInt();
        //addition of the numbers
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
    //initializing variable
        int numb;
        //users input
        Scanner input = new Scanner(System.in);
        System.out.print("Enter number : ");
        numb = input.nextInt();
        //if statement using modulo operator
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
    //initializing variables
      int num1,num2,num3; 
      //users input
      Scanner input = new Scanner (System.in);
      System.out.print("Enter first number : ");
      num1 = input.nextInt();
      System.out.print("Enter second number : ");
      num2 = input.nextInt();
      System.out.print("Enter third number : ");
      num3 = input.nextInt();
      //if eles statement comparing 3 numbers 
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

9. Write a Java program to print the multiplication table of any number.
    ANSWER
package cos261test;
import java.util.Scanner;

public class Cos261Test {
    public static void main(String[] args) {
    //initializing variable
      int num1;  
      //users input
      Scanner input = new Scanner (System.in);
      System.out.print("Enter number : ");
      num1 = input.nextInt();
      System.out.print("Multiplication Table for " + num1 + " :");
      //for statement for multiplication
        for (int i = 0; i < 12; i++) {
            System.out.println(num1 + " x " + i + " = " + (num1 * i));
        }
    }
}

run:
Enter number : 5
Multiplication Table for 5 :5 x 0 = 0
5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
5 x 4 = 20
5 x 5 = 25
5 x 6 = 30
5 x 7 = 35
5 x 8 = 40
5 x 9 = 45
5 x 10 = 50
5 x 11 = 55
BUILD SUCCESSFUL (total time: 2 seconds)

![Screenshot (16)](https://github.com/user-attachments/assets/de140ff4-fede-4c78-85cd-9e51a7d0d596)

OOP Concepts
11. Create a class student with properties name, matricNo, and score, and add method to display the student's info.
    ANSWER
package cos261test;

public class Cos261Test {
//properties of the student
    String name;
    String matricNo;
    double score;
    //constructor to intiliaze student
    public Cos261Test(String name, String matricNo, double score) {
    this.name = name;
    this.matricNo = matricNo;
    this.score = score;
    }
    //the method to diplay student info
    public void displayInfo(){
    System.out.print("Name :" + name);
    System.out.print("\nMatric Number :" + matricNo);
    System.out.print("\nScore : " + score);
    }
    //method of testing the class
    public static void main(String[] args) {
    //creating a student object with simple data
        Cos261Test stud = new Cos261Test(" Nwodo Ebenezer", " 2023/253257", 85.5);
        //displaying the student's info
        stud.displayInfo();
        System.out.println();
    }
}

run:
Name : Nwodo Ebenezer
Matric Number : 2023/253257
Score : 85.5
BUILD SUCCESSFUL (total time: 0 seconds)

![Screenshot (17)](https://github.com/user-attachments/assets/2cd44536-46f6-4fee-b879-68025282c496)

