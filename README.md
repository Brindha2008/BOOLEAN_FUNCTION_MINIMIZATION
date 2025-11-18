# BOOLEAN_FUNCTION_MINIMIZATION
Date:18/11/2025

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


Developed by:Brindha A R


RegisterNumber:25013493


**RTL realization Output:


<img width="1181" height="745" alt="Screenshot 2025-11-18 212740" src="https://github.com/user-attachments/assets/f022cf3b-4ca9-4822-a02b-6a0573b22fb4" />

**Output:**

**RTL**
<img width="1458" height="485" alt="Screenshot 2025-11-18 212710" src="https://github.com/user-attachments/assets/8c118664-d32a-4762-8ca2-8547081e672e" />

**Timing Diagram**

**Result:**
Thus, the given logic functions are implemented using logic gates and their operations are verified using Verilog programming.



