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
i) 
module boolean(a,b,c,d,f1); 
input a,b,c,d; 
output f1; 
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c)); 
endmodule 
ii) 
module bool(w,x,y,z,f2); 
input w,x,y,z; 
output f2; 
assign f2=((~y & z)|( w & y )|(x & y)); 
endmodule
```
Developed by: DHIVYASHREE .R RegisterNumber: 25016639

**RTL realization**
<img width="1528" height="791" alt="Screenshot (106)" src="https://github.com/user-attachments/assets/8b9d0e2d-f56b-4193-881e-1a7fa4e84c16" />


**Output:**
<img width="1393" height="681" alt="Screenshot (107)" src="https://github.com/user-attachments/assets/7cbdb4e1-b858-4f79-a6a0-650aad6dbe51" />


**RTL**
<img width="1324" height="639" alt="Screenshot (108)" src="https://github.com/user-attachments/assets/6257b8e0-b019-4609-9dfb-3b213d08ac9b" />


**Timing Diagram**
<img width="1336" height="709" alt="Screenshot (109)" src="https://github.com/user-attachments/assets/68a3f218-6571-46cc-8fc8-bdafa16acb66" />


**Result:**
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

