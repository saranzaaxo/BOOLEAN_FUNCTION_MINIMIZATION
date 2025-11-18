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
```
F(A,B,C,D)=AB+CD+AD

module boolean_function_4var (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule

```

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:SARANRAJ R RegisterNumber:25018491


**RTL realization**
<img width="936" height="465" alt="image" src="https://github.com/user-attachments/assets/1d75ebe3-fe08-4bea-8ded-d4d010ab9952" />

**Output:**
<img width="964" height="474" alt="image" src="https://github.com/user-attachments/assets/128f65d2-ccbe-4b34-b7ff-db18db2d4661" />

**RTL**

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

