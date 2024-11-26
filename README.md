# BOOLEAN_FUNCTION_MINIMIZATION

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

Developed by :sanjay a RegisterNumber:24010848*/
```
module exp2(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c)); 
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

**RTL OUTPUT**

![Screenshot 2024-11-06 030646](https://github.com/user-attachments/assets/02b82286-165b-42d7-9202-bede6d0cc216)




**Timing Diagram**

![screen shoot 2](https://github.com/user-attachments/assets/6151b8e5-c737-4a6a-8c27-6d24b347e2a7)
**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

