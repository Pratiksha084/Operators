# Operators
THEORY

An operator is a symbol that operates on a value to perform specific mathematical or logical computations. They form the foundation of any programming language. In C++, we have built-in operators to provide the required functionality.

An operator operates the operands. For example, 

int c = a + b;

Here, ‘+’ is the addition operator. ‘a’ and ‘b’ are the operands that are being ‘added’.

Operators in C++ can be classified into 6 types:
Arithmetic Operators

Relational Operators

Logical Operators

Bitwise Operators

Assignment Operators

Ternary or Conditional Operators

1) Arithmetic Operators
These operators are used to perform arithmetic or mathematical operations on the operands. For example, ‘+’ is used for addition, ‘-‘ is used for subtraction ‘*’ is used for multiplication, etc. 

Arithmetic Operators can be classified into 2 Types:

A) Unary Operators: These operators operate or work with a single operand. For example: Increment(++) and Decrement(–) Operators.

Name	Symbol	Description	Example
Increment Operator	++	 Increases the integer value of the variable by one	
int a = 5;

a++; // returns 6

Decrement Operator	—	 Decreases the integer value of the variable by one	
int a = 5;

a–; // returns 4

Example:

the description

Output
a++ is 10

++a is 12

b-- is 15

--b is 13

Note: ++a and a++, both are increment operators, however, both are slightly different.

In ++a, the value of the variable is incremented first and then It is used in the program. In a++, the value of the variable is assigned first and then It is incremented. Similarly happens for the decrement operator.


B) Binary Operators: These operators operate or work with two operands. For example: Addition(+), Subtraction(-), etc.


Addition	+	Adds two operands	
int a = 3, b = 6;


int c = a+b; // c = 9

Subtraction	–	Subtracts second operand from the first	

int a = 9, b = 6;

int c = a-b; // c = 3

Multiplication	*	Multiplies two operands	

int a = 3, b = 6;

int c = a*b; // c = 18

Division	/	Divides first operand by the second operand 	

int a = 12, b = 6;

int c = a/b; // c = 2

Modulo Operation	%	Returns the remainder an integer division	

int a = 8, b = 6;

int c = a%b; // c = 2


ALGORITHM

Enter Your PRN
1.It declares two integer variables prn and digit to store the PRN and individual digits, respectively.

2.It prompts the user to enter their PRN.

3.It enters a while loop that continues as long as prn is greater than 0.

4.Inside the loop:

5.It calculates the last digit of prn using the modulo operator (%) and assigns it to the digit variable.

6.It prints the digit on a new line.

7.It divides prn by 10 to remove the last digit.

8.The loop continues until all digits of the PRN have been extracted and printed.

Enter marks of each subjects and find the grade based on average
1.It declares integer variables sub1, sub2, sub3, sub4, sub5 to store the marks of five subjects, and variables sum and average to store the sum of marks and the average, respectively.

2.It prompts the user to enter marks for each subject.

3.It calculates the sum of the marks from all five subjects.

4.It calculates the average by dividing the sum by 5.

5.It uses a series of if and else if statements to determine the grade based on the average:

6.If the average is greater than or equal to 90, it assigns the grade "O."

7.If the average is between 85 and 89, it assigns the grade "A+."

8.If the average is between 75 and 84, it assigns the grade "A."

9.If the average is between 65 and 74, it assigns the grade "B+."

10.If the average is between 55 and 64, it assigns the grade "B."

11.If the average is between 40 and 54, it assigns the grade "C."

12.If none of the above conditions are met, it assigns the grade "Student has failed."

13.It prints the grade based on the average.

EXPECTED OUTPUT

PRN CODE

Enter your prn:

123088

8

8

0

3

2

1

GRADE CODE

Enter your marks for each subjects;

99

100

98

97

97

Grade is O


