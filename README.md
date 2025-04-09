# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software**
```
Quartus prime
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

![e0070843-a252-4c47-888c-8dd2123bfbea](https://github.com/user-attachments/assets/3148b487-c047-4614-9f6d-cae761d379c3)
![65199166-e54c-40d1-8d92-a2e45fab5b41](https://github.com/user-attachments/assets/99ffdc6c-96a7-4999-918c-08413a6c7127)



**Output:**

![EXP-2](https://github.com/user-attachments/assets/38080591-c2ed-437b-8b49-ef9392edc77c)

**RTL**

![EXP-2 (2)](https://github.com/user-attachments/assets/42dcb96b-a6df-4d81-b569-0b600fc7687d)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

