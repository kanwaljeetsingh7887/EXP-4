# EXP-4
EXP 3
Aim:
To study and implement Operators in C++

Software:
Microsoft VSCode

Theory:
Opeartors in C++ are the symbols that are used two perform some mathematocalor logical operations on the variables. They are classified into 6 types:

1. Arithmetic Operators:

Addition (+): Adds two operands.
Subtraction (-): Subtracts the second operand from the first.
Multiplication (*): Multiplies two operands.
Division (/): Divides the first operand by the second.
Modulus (%): Returns the remainder of division.
2. Relational Operators:

Equal to (==): Checks if two values are equal.
Not equal to (!=): Checks if two values are not equal.
Greater than (>): Checks if the first value is greater than the second.
Less than (<): Checks if the first value is less than the second.
Greater than or equal to (>=): Checks if the first value is greater than or equal to the second.
Less than or equal to (<=): Checks if the first value is less than or equal to the second.
3. Logical Operators:

Logical AND (&&): Returns true if both operands are true.
Logical OR (||): Returns true if at least one operand is true.
Logical NOT (!): Reverses the logical state of its operand.
4. Assignment Operators:

Simple assignment (=): Assigns the value on the right to the variable on the left.
Add and assign (+=): Adds the right operand to the left operand and assigns the result to the left operand.
Subtract and assign (-=): Subtracts the right operand from the left operand and assigns the result to the left operand.
Multiply and assign (*=): Multiplies the left operand by the right operand and assigns the result to the left operand.
Divide and assign (/=): Divides the left operand by the right operand and assigns the result to the left operand.
Modulus and assign (%=): Takes the modulus using the left and right operands and assigns the result to the left operand.
5. Bitwise Operators:

AND (&): Performs a bitwise AND.
OR (|): Performs a bitwise OR.
XOR (^): Performs a bitwise XOR.
NOT (~): Performs a bitwise NOT.
Left Shift (<<): Shifts bits to the left.
Right Shift (>>): Shifts bits to the right.

## Code: 3B
```
//KANWALJEET SINGH
//ENTC B2
//EXP 3B
//23070123124
#include<iostream>
using namespace std;
int main(){
    int a=5;
    int b=6;
    
    cout << "\nBitwise Operators:" << endl;
    cout << "AND (a & b): " << (a & b) << endl;
    cout << "OR (a | b): " << (a | b) << endl;
    cout << "XOR (a ^ b):" << (a ^ b) << endl;
    cout << "NOT (~a) : " << (~a) << endl;
    cout << "LEFT SHIFT (a << 1):" << (a << 1) << endl;
    cout << "RIGHT SHIFT (a >> 1) : " << (a >> 1) << endl;
return 0;
}

```
## Output:
![image](https://github.com/user-attachments/assets/470c3df3-1a7b-4d9f-9075-229f0f4eeeda)
