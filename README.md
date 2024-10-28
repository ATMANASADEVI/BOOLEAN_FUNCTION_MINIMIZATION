# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory** 

![image](https://github.com/user-attachments/assets/3efa61a9-e383-48b4-968b-c5039f11a9fa)


**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

module Exp2(a,b,f_and,f_or,f_nor,f_not,f_nand,f_xor,f_xnor);
input a,b;
output f_and,f_or,f_nor,f_not,f_nand,f_xor,f_xnor;
and(f_and,a,b);
or(f_or,a,b);
nor(f_nor,a,b);
not(f_not,a);
nand(f_nand,a,b);
xor(f_xor,a,b);
xnor(f_xnor,a,b);
endmodule

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:*/

**RTL realization**![Screenshot (20)](https://github.com/user-attachments/assets/06451756-35c4-4fd7-a351-5ae7583b6d8a)

**Timing Diagram**![image](https://github.com/user-attachments/assets/a7a0908d-e538-4926-8013-cdafb8383ec3)

**Result:**
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

