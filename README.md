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


**Program:*
~~~~
module ha_dataflow(a, b, s, ca); 
    input a; 
    input b; 
    output s; 
    output ca; 
  assign#2 s=a^b; 
  assign#2 ca=a&b;
  endmodule
~~~~
~~~
Developed by: SARANYA AV
RegisterNumber: 24900084
~~~~


**RTL realization**
![image](https://github.com/user-attachments/assets/1a8f4605-05b4-47ce-9a09-a657d9799703)

**Timing Diagram**
![image](https://github.com/user-attachments/assets/56b64bc8-b725-41c0-a493-ffe11a17c757)

**Output**

Hence we have implemented the given logic function and verified its operation in Quartus using Verilog programming.

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

