# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software**
```
Quartus Prime
Modelism Altera

```

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
```
input A,B,C,D,w,x,y,z;
output f1,f2;
assign f1=((~B&~D)|(~A&B&D)|(A&B&~C));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule 
```
```

Developed by:PRIYA.B
RegisterNumber:21224230208
```

**TRUTH TABLE**
![Screenshot 2025-03-14 082328](https://github.com/user-attachments/assets/148b758a-8042-416b-b75e-b1e3ae92ec9f)

**Output:**
![EXP-2](https://github.com/user-attachments/assets/81556ec2-088b-4f67-b250-7bcb704e3f86)

**RTL**
![EXP-2 (2)](https://github.com/user-attachments/assets/fd9e865a-5d91-4f19-a9df-4828e227d6f3)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

