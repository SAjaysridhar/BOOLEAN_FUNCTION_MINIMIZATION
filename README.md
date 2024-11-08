# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
![WhatsApp Image 2024-10-22 at 10 20 22_77e36bfd](https://github.com/user-attachments/assets/0e3f9187-53d5-446f-b52f-8245023f8539)

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
module ex2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~c)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:24900457


**RTL**
![WhatsApp Image 2024-11-05 at 10 12 55_8dd36c79](https://github.com/user-attachments/assets/2c1b742c-27c4-4621-9282-380382e0a00a)

**Timing Diagram**
![WhatsApp Image 2024-11-05 at 11 10 12_655a23e3](https://github.com/user-attachments/assets/759e5773-ed52-438a-b0e0-1dc4fe911ac7)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

