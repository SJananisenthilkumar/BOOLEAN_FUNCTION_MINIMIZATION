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
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: JANANI S
RegisterNumber: 212223230086
module boolean(e, f, a, b, c, d);
output e, f;
input a, b, c, d;
assign e = a || (b && c) || ((!b) && d);
assign f = ((!b) && c)|| (b && (!c) && (!d));
endmodule
```

**RTL realization**
![Screenshot (111)](https://github.com/SJananisenthilkumar/BOOLEAN_FUNCTION_MINIMIZATION/assets/144871139/0fcb2868-e1cc-4a08-89af-dd57c8a118da)

**RTL**
![boolean](https://github.com/SJananisenthilkumar/BOOLEAN_FUNCTION_MINIMIZATION/assets/144871139/7e9b4155-5e04-4a5e-94f7-b126111c88c7)

**Timing Diagram**
![Screenshot (109)](https://github.com/SJananisenthilkumar/BOOLEAN_FUNCTION_MINIMIZATION/assets/144871139/b5acb6d5-b8eb-43d1-8b51-65dbb09bd89e)

**Result:**
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

