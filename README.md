# Bitwise Operators in C
The bitwise operators are the operators used to perform the operations on the data at the bit-level.
<br> <br>



| Operator      | Meaning                     |
| ------------- |:-------------:              |
| &             |Bitwise AND operator         |
| 1             |Bitwise OR operator          |
| ^             |Bitwise exclusive OR operator|
| <<            |Left shift operator          |
| >>            |Right shift operator         |

![image](https://user-images.githubusercontent.com/125560933/227697906-2166c975-90f5-4697-974a-a7879c76914e.png)

    Example:
    We have two variables a and b. 
    a =6;  
    b=4;  
    The binary representation of the above two variables are given below:  
    a = 0110  
    b = 0100  
    When we apply the different bitwise operation in the above two variables, the output would be:  
    a&b -  Result = 0100  i.e 4 
    a|b -  Result = 0110  i.e 6 
    a^b -  Result = 0010  i.e 2 
    
Right Shift Operator <br>
Right shift operator shifts all bits towards right by certain number of specified bits. It is denoted by >> .

    a = 0111
    a>>2 ;  
    0000 0111 >> 2 = 0000 0001 
    
 Left-shift operator <br>
It is an operator that shifts the number of bits to the left-side.

    a = 0101  
    a << 2;  
    0101<<2 = 00010100 

## To check if the number is even or odd using BITWISE Operator:

        ALGORITHM:
        1. Input a number from user.
        2. Check if (num & 1)
        3. If true , the number is odd.
        4. Else , Even.

