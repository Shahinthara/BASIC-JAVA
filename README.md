BASIC
1.class CodeChef
{
	public static void main (String[] args)
	{
		System.out.println(12);
	}
}
Your Output
12


2.we want to output "I love Java"

class CodeChef
{
	public static void main (String[] args)
	{
		System.out.println("I love java");
	}
}
Your Output
I love java

3.Try to add 21 and 40 in code and print the result.

class CodeChef
{
	public static void main (String[] args)
	{
		System.out.println(21 + 40);
	}
}
Your Output
61


Types of Comments in Java
1.Single-Line Comments:
2.Multi-Line Comments:

Task
Write a program which does the following:

Add a println statement and output the sum of 3 + 4.
Add another println statement and output the sum of 2 + 1.


class CodeChef
{
	public static void main (String[] args)
	{
		System.out.println(3+4);
		System.out.println(2+1);
		
	}
}
Your Output
7
3

Area & Perimeter of Rectangle
Write a program for the following problem:

Let’s consider a rectangle of sides 11 and 13
Find and output area of the rectangle having sides 11 and 13
Find and output perimeter of the rectangle having side as 11 and 13

For any rectangle, the formula for area is length * breadth.
The formula for perimeter is 2 * (length + breadth).

class CodeChef
{
	public static void main (String[] args)
	{
		System.out.println(11 * 13);
		
		System.out.println(2*(11 + 13));
	}
}

Your Output
143
48

class Codechef {
  public static void main(String[] args) {
    System.out.println("Hello");
    System.out.println("World");
  }
}

Printing text and number together
1.System.out.println("The numeric value of twenty three is " + 23);

// Output:
// The numeric value of twenty three is 23

2.System.out.println("The sum of 20 and 40 is " + (20 + 40));

// Output:
// The sum of 20 and 40 is 60
3.class Codechef
{
	public static void main (String[] args)
	{
		System.out.println("2 times 5 is " + (10));
	}
}
Your Output
2 times 5 is 10

Inserting space between numbers
class Codechef
{
	public static void main(String[] args)
	{
		System.out.println(7 + " " + 3);
	}
}
output
7 3

Task
Write a program which does the following:

Print the result of subtraction of 9 and 2.
Print the result of division of 30 by 5.

class Codechef
{
	public static void main (String[] args)
	{
		System.out.println(9 - 2);
		System.out.println(30 / 5);
	}
}

Your Output
7
6

Task
Write the exact code which we discussed in this lesson, to output the sum of 12 and 7.
class CodeChef
{
    public static void main(String[] arg)
    {
        System.out.println(12 + 7);
    }
}

Your Output
19

Variables in Java
**int denotes that we will be storing integers (numbers) in this variable.
Task
Create a variable in editor named age and assign the value 25 to it.
Print the value of age variable using print statement.

class Codechef
{
	public static void main (String[] args)
	{
	    int age = 25;
	    System.out.println(age);
	}
}
Your Output
25

Declaring a variable
Data Type	Description	                     Example Declaration
int	      Stores integers	                       int c = 100000;
long	      Stores larger/smaller integers	       long d = 100000L;
float	      Stores small decimal numbers	       float e = 10.5;
double	      Stores large decimal numbers	       double f = 10.5;
char	      Stores single characters	               char g = 'A';
boolean	      true or false value	               boolean h = true;
String        Stores text 
             (a sequence of characters)	               String i = "Hello";

Task
Write a program which does the following:

Create an integer variable named number.
Assign the value 19 to number.
Output the value of number.

class Codechef
{
	public static void main (String[] args)
	{
       int number = 19;
        System.out.println(number);
	}
}

Your Output
19


Addition of Variables
Write a program which does the following:

Declare two integer variables a and b.
Assign the value 23 to a and 20 to b.
Output the sum of a and b to the console.

class Codechef
{
	public static void main (String[] args)
	{
	   int a=23;
	   int b=20;
	   System.out.println(a+b);
	}
}

Your Output
43


Area of Rectangle
Write a program which does the following:

Find out and display the area of a rectangle of sides 45 and 76 respectively.
Declare variables length, width and area and assign the relevant values to them.
Print the area of the rectangle.


class Codechef
{
	public static void main (String[] args)
	{
	   // Update the blanks in the code below
        int length = 45;
        int width = 76;
        int area = length * width;
        System.out.println("The Area of the given rectangle is " + (area));
	}
}

Your Output
The Area of the given rectangle is 3420

Double datatype
If we want to store decimal values we use the double data type.

Syntax to declare a double:

double radius = 8.9;

Task
Write a program which does the following:

Find the area of a circle whose radius is 8.9. Take pi = 3.14.
Declare variables radius, pi and area and assign the relevant values to them.
Formula for area of a circle is Pi * radius * radius.

class Codechef
{
	public static void main (String[] args)
	{
		double pi = 3.14;
		double radius = 8.9;
		double area = pi * radius * radius;
		System.out.println("The Area of the given Circle is " + area);
	}
}
Your Output
The Area of the given Circle is 248.71940000000004

String Datatype
The string type is used to store a sequence of characters, i.e. text.
String values must be surrounded by double quotes, i.e. " ".

The syntax to declare a string is:

String site = "CodeChef";
We can use + to join two strings:

String a = "Ja";
String b = "va";
System.out.println(a + b);

// Output:
// Java

Task
Write a program which does the following:

Declare two string variables a & b.
Assign the values "Code" to a and "Chef" to b.
Display the variables in a single line without any space between them.


class Codechef
{
	public static void main (String[] args)
	{
	    String a = "Code";
	    String b = "Chef";
	    System.out.println(a+b);
        
	}
}
Your Output
CodeChef


Bool Datatype
boolean studying = true;
System.out.println(studying);

// Output:
// true


boolean studying = true;
System.out.println(studying);

// Output:
// true

Task
Write a program which does the following

Declare two variables x and y
Assign the value true to x and the value false to y
Output x and y on separate lines

class Codechef
{
	public static void main (String[] args)
	{
        boolean x=true; 
        System.out.println(x);
        boolean y=false;
        System.out.println(y);
    }
}
Your Output
true
false


Cost of painting
Write a program which does the following:

Find the area of a square of side 14 cm.
Also, find the cost of painting the square if the paint costs is $7 per cm^2
Initialise the following variables in your program and use them in the computation
s to store the length of side the square.
area to store the area of the square.
cost to store the cost of painting.
Output area and cost to the console on separate lines.

class Codechef
{
	public static void main (String[] args)
	{
		int s = 14 ;
        int area = s * s;
        int cost = area * 7 ;
        System.out.println(area);
        System.out.println(cost);
	}
}
Your Output
196
1372


Task
Write a program which does the following:

Display the sum, product, and quotient of 2 integers : -50 & 40.
Initialise the following variables in your program and use them in the computation.
Variable a and assign it the value -50.
Variable b and assign it the value 40.
Variables sum, product and quotient - assign the relevant values to them:
sum = a + b
product = a * b
quotient = a / b
Note - sum, product and quotient need to be integers.

Output sum, product and quotient to the console on separate lines.


class Codechef
{
	public static void main (String[] args)
	{
		int a = -50;
		int b = 40;
		int sum=a+b;
		System.out.println(sum);
		int product=a*b;
		System.out.println(product);
		int quotient=a/b;
		System.out.println(quotient);
	}
}
Your Output
-10
-2000
-1

Compound Assignment Operators
There are also compound assignment operators that perform an operation and then assign the result back to the variable. Let's look at a few:

x -= 5        (Subtracts 5 from x and assigns the result back to x)
x *= 3        (Multiplies x by 3 and assigns the result back to x)
x /= 3        (Divides x by 3 and assigns the result back to x)
x %= 3        (Finds the remainder when x is divided by 3 and assigns the result back to x)
Task
Using an assignment operator, output the remainder when length is divided by 3.


class Codechef
{
	public static void main (String[] args)
	{
	    int length = 11;
	    length%=3;
	    System.out.println(length);
		
	}
}

Your Output
2

Basic Comparison
Here are some more examples of relational operators:

a > b          (Checks if a is greater than b)
a == b        (Checks if a is equal to b)
a != b        (Checks if a is not equal to b)
a >= b        (Checks if a is greater than or equal to b)
a <= b        (Checks if a is less than or equal to b)

Task
You are given two variables height1 and height2.
Output true if they are equal else false.

import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
	    int height1 = 15;
	    int height2 = 13;
	    System.out.println(height1 == height2);
	}
}
Your Output
false

Basic Logical Operations
Here are the basic logical operators and their usage:

&&   (Logical AND: returns true only if both conditions are true)
a > 5 && a < 10  // returns true only if a is greater than 5 but less than 10
||  (Logical OR: returns true if at least one condition is true)
a > 10 || a < 5  // returns true if a is greater than 10 or less than 5
!   (Logical NOT: reverses the result of the condition)
!(a > 5 && a < 10) // returns true in the opposite cases of the first condition above

Task
You are given a variable height.
You are allowed to enter the waterpark only if your height is between 5 and 10 (Inclusive).
Apply the condition and output 
1
1 if condition is true or 
0
0 if condition is false as applicable.

public class Main {
    public static void main(String[] args) {
        int height = 15;
        // Update the blanks in the code below
        if(5<height && height>15)
        {
            System.out.println(1);
        }
        else{
            System.out.println(0);
        }
    }
}
Your Output
0

Conditional Operator
Syntax:
condition ? value_if_true : value_if_false;
Explanation:
condition: This is the expression to be evaluated. If it is true, the operator returns value_if_true; otherwise, it returns value_if_false.
value_if_true: This is the value returned if the condition evaluates to true.
value_if_false: This is the value returned if the condition evaluates to false.
Example:
int a = 10, b = 5;
int max = (a > b) ? a : b;
In this example:

(a > b) is the condition.
a is value_if_true.
b is value_if_false.
If a is greater than b, max will be assigned the value of a; otherwise, it will be assigned the value of b.

Task
Given an integer, print 0 if its odd, else print 1.
public class Main {
    public static void main(String[] args) {
        int num = 15;
        System.out.println((num % 2 == 1) ? 0 : 1);
    }
}

Your Output
0

Solve this problem - 1
You are given the age of a person as the variable age.
Will this person be able to vote?
Output 1 or 0 assuming that the voting age is 18
i.e., a person's age has to be greater than or equal to 18 to vote.

public class Main {
    public static void main(String[] args) {
        int age = 20;
        // Update the blank in code below
        System.out.println((age >= 18) ? 1 : 0);
    }
}
Your Output
1


Solve this problem - 2
You are given the name of a teen as the variable name.
There is a special rule in Chef town - You will get special treatment if your name is C or A.

Output the following:

1 if the name is A or C.
0 otherwise.

public class Main {
    public static void main(String[] args) {
        char name = 'D';
        // Update the blank in code below
        System.out.println((name=='C'||name=='A') ? 1 : 0); // Use single quotes for individual characters
        }
    }

Your Output
0

Operator Precedence

Type conversion and type casting
Example:

int a = 5;
float b = 2.5f; // note the 'f' suffix to denote a float literal in Java
float result = a + b; // 'a' is automatically changed to a float before adding.
System.out.println(result);  // prints 7.5


Example:

int a = 10;
int b = 3;
float result = (float)a / b; // Here, 'a' is explicitly changed to a float before dividing.
System.out.println(result);  // prints 3.33

Task
In the IDE, create a variable result of type float which stores the result with decimal value when a is divided by b, then print it.

public class Main {
    public static void main(String[] args) {
        int a = 14;
        int b = 5;
        float result = (float)a / b;
        System.out.println(result);
    }
}
Your Output
2.8

INCREMENT AND DECREMENT
public class Main {
    public static void main(String[] args) {
        int a = 5;
        int b = 3;
        int result = a++ - --b + a--;
        System.out.println(result);
    }
}
- a++: 5 (increments a to 6 for future use)
- --b: 2
- a--: 6 (decrements a to 5 for future use)

Now, perform the arithmetic:
5 - 2 + 6 = 9
So, result will be 9.


Coding problem - 3
Hrishi is still learning Java.
However - it seems his knowledge of type casting, variables and output is still incomplete.
The code given in the IDE is incorrect.
Hrishi wanted to output Result: 2.50.
Click on 'Run' to see the current output - Can you debug the code to get the desired output?

public class Main {
    public static void main(String[] args) {
        double x = 5.00;
        int y = 2;
        float result = (float)(x / y);
        System.out.printf("Result: %.2f\n", result);
    }
}

public class Main {
    public static void main(String[] args) {
        double x = 5.00;
        int y = 2;
        float result = (float)(x / y);
        System.out.printf("Result: %.2f\n", result);
    }
}

public class Main {
    public static void main(String[] args) {
        double x = 5.00;
        int y = 2;
        float result = (float)(x / y);
        System.out.printf("Result: %.2f\n", result);
    }
}

public class Main {
    public static void main(String[] args) {
        double x = 5.00;
        int y = 2;
        float result = (float)(x / y);
        System.out.printf("Result: %.2f\n", result);
    }
}

Your Output
Result: 2.50

Debugging Problem
In the IDE a program is given to convert a temperature from Fahrenheit to Celsius. It takes the temperature in Fahrenheit as input from the user and output the temperature in Celsius.

The formula for conversion is:

C = ((F−32) × 5) / 9
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        float f = 49;
        float c = ((f - 32) * 5) / 9; 
        
        System.out.println(c);
    }
}
Your Output
9.444445
