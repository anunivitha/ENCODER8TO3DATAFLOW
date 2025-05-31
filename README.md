### ENCODER 8TO3 DATAFLOW Modelling

**AIM:**

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:** Quartus prime

**THEORY**

**Encoder 8 To 3**

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/0bc242c1-eb9e-4c47-afe5-30428470efc3)

Figure 01  Block Diagram of Encoder 8 * 3

**Truth Table**

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/35496b14-ae6e-4cd1-9abd-d6736b576575)

The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/95acaee6-c873-4c75-89eb-ef09fb158053)

Figure 02  Encoder 8 * 3

**Procedure**

/* write all the steps invloved */

**PROGRAM**

/* Program for Encoder 8 To 3 in Dataflow Modelling and verify its truth table in quartus using Verilog programming. 

Developed by: Anu Nivitha U
RegisterNumber: 212223040016
*/
```
<img width="531" alt="Screenshot 2025-05-31 at 10 05 29 PM" src="https://github.com/user-attachments/assets/8474a437-91b4-4fce-a3c9-553ccde7d441" />

```

**RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling**
<img width="693" alt="Screenshot 2025-05-31 at 10 05 35 PM" src="https://github.com/user-attachments/assets/f0a2d678-4c82-4034-a16f-b247c025027f" />


**TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling**
<img width="706" alt="Screenshot 2025-05-31 at 10 05 41 PM" src="https://github.com/user-attachments/assets/f5936fd4-fb04-450e-9c03-262c643b2f48" />


**RESULTS**

Implementing Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables executed succesfully.


