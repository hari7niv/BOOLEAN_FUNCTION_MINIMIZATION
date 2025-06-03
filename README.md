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

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. */

```
Developed by: Shailesh Kumar G
RegisterNumber: 212224220093
```

```
module exp2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
endmodule
```

```
module exp2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
endmodule
```

**RTL realization**

**Output:**

**F1:**

![image](https://github.com/user-attachments/assets/71ff85ce-ff6a-41a4-adef-bbb6b1e79866)

**F2:**

![image](https://github.com/user-attachments/assets/84586a4d-c200-496c-aad2-f995733454b0)

**RTL**

## F1:
![image](https://github.com/user-attachments/assets/4b4a4e99-f254-475d-8d54-9f3f6f19e596)

## F2:

![image](https://github.com/user-attachments/assets/fbf04df4-2f92-4ed0-973e-9da1079b4f51)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

