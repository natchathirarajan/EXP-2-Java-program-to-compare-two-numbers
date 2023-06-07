# EXP-2-Java-program-to-compare-two-numbers

## AIM:
To write a java program to compare two numbers.

## ALGORITHM: 
### Step 1:
Import the necessary packages.
### Step 2: 
Get the two values from the user.
### Step 3: 
Compare the two numbers using if else statements conditions.
### Step 4:  
Print the result.
### Step 5: 
End the program.
## PROGRAM:

~~~
import java.util.*;
public class Main {
    public static void main(String [] args){
        Scanner s= new Scanner(System.in);
        System.out.println("Enter first number :");
        int num1= s.nextInt();
        System.out.println("Enter second number :");
        int num2=s.nextInt();

        if (num1 == num2){
            System.out.println("They are equal");
        }
        else if (num1 > num2) {
            System.out.println(num1+ " is GREATER than " +num2);
        }
        else {
            System.out.println(num2+" is GREATER than "+ num1);
        }
    }
}
~~~

## OUTPUT:
![out](https://github.com/abdulwasih2003/EXP-2-Java-program-to-compare-two-numbers/assets/91781810/960e88fa-c829-4855-b285-80a0b22328b4)

## RESULT:
Thus the java program to compare two numbers is successful.



