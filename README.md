![EXP-2 (2)](https://github.com/user-attachments/assets/63eb956d-2744-4fe5-b290-149bd7372938)# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
```
module EXP2(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```
```

Developed by:PRIYA.B
RegisterNumber:212224230208
```


**TRUTH TABLE**
![Screenshot 2025-03-14 082328](https://github.com/user-attachments/assets/36121ca8-274a-4b3d-878d-df7af38f800f)

**RTL**
![EXP-2](https://github.com/user-attachments/assets/3de25e2e-8c73-46ae-93bd-c71b0d1f1891)


**Output:**
![EXP-2 (2)](https://github.com/user-attachments/assets/dee77d18-8eed-4273-85b2-43f5fdc275fd)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

