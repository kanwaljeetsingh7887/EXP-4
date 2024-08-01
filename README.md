# EXP-4

## Aim:
**To study and implement C++ Bitwise Operators.**

## Software:
`Microsoft VSCode`

## Theory:
Bitwise operators perform operations on the `binary` representations of integers. They are useful for low-level programming tasks, such as manipulating data at the bit level or optimizing performance in critical sections of code.

**Overview of Bitwise Operators:**

 **1. Bitwise AND `(&)`:**
 Compares each bit of two operands; the result has a bit set to `1` only if both corresponding bits of the operands are `1`.
 
 **2. Bitwise OR `(|)`:**
 Compares each bit of two operands; the result has a bit set to `1` if either of the corresponding bits of the operands is `1`.
 
 **3. Bitwise XOR `(^)`:**
 Compares each bit of two operands; the result has a bit set to `1` if only one of the corresponding bits of the operands is `1`, but not both.
 
 **4. Bitwise NOT `(~)`:**
 Inverts all the bits of the operand. Each 0 becomes `1` and each 1 becomes `0`.
 
 **5. Left Shift `(<<)`:**
 Shifts the bits of the operand to the left by the specified number of positions. New bits on the right are set to `0`.
 
 **6. Right Shift `(>>)`:**
 Shifts the bits of the operand to the right by the specified number of positions. The sign bit is used for the new bits on the left `(arithmetic shift)`.
 


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

## Conclusion:
Bitwise Operators are essential for tasks such as implementing efficient algorithms, controlling hardware etc. We learned how to use Bitwise Operators and implement them efficiently in C++ programming.
