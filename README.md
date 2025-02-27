# EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM

 # NAME : Vignesh M
 # REGISTER NUMBER : 212223240176
 # DEPARTMENT :AIML

## Aim:
To implement and verify the functioning of basic logic gates (AND, OR, NOT, NAND, NOR, XOR) using a PLC ladder program and simulate the outputs.</br>

## Apparatus Required:
Programmable Logic Controller (PLC) - A PLC with support for ladder logic programming.</br>
PLC Programming Software - Software like RSLogix, TIA Portal, or CX-Programmer.</br>
Computer System - To run the PLC programming software and perform simulations.</br>
Input Devices - Push buttons or switches to simulate inputs (I/O modules).</br>
Output Devices - LEDs or any indicator to visualize the output of logic gates (I/O modules).</br>
Wires and Connectors - For connecting input/output devices to the PLC.</br>
Power Supply - Appropriate power supply for PLC and peripherals.</br>

## Theory:
Logic gates are the fundamental building blocks of digital circuits, and they process binary inputs to produce a binary output. In PLC programming, these logic gates can be implemented using ladder logic, which is a graphical programming language resembling electrical relay logic.</br>

## Basic Logic Gates:

#### AND Gate:</br>

Function: Outputs HIGH only when all inputs are HIGH.</br>
Ladder Logic: Represented by two or more normally open contacts in series.</br>

#### OR Gate:</br>

Function: Outputs HIGH when at least one input is HIGH.</br>
Ladder Logic: Represented by two or more normally open contacts in parallel.</br>

### NOT Gate:</br>

Function: Outputs the inverse of the input signal.</br>
Ladder Logic: Represented by a normally closed contact.</br>

### NAND Gate:</br>
Function: Outputs LOW only when all inputs are HIGH.</br>
Ladder Logic: An AND gate followed by a NOT gate.</br>

### NOR Gate:</br>

Function: Outputs LOW when at least one input is HIGH.</br>
Ladder Logic: An OR gate followed by a NOT gate.</br>

#### XOR Gate:</br>

Function: Outputs HIGH when an odd number of inputs are HIGH.</br>
Ladder Logic: Represented by a combination of AND, OR, and NOT gates.</br>

## Truth Tables:

 ### AND GATE:
 

 ### OR GATE:
 
 ![image](https://github.com/user-attachments/assets/f0fd4784-ae28-4161-ab73-d1097ffc4be6)

### NOT GATE:

![image](https://github.com/user-attachments/assets/8b29c5e5-2507-49fa-be88-c92e4f43779d)

### NAND GATE:

![image](https://github.com/user-attachments/assets/037f1140-ef47-4f02-97f9-e1b560122009)

### NOR GATE:
![image](https://github.com/user-attachments/assets/b7287452-bd63-42cf-8c1d-bda5479be303)

### EX-OR GATE:

![image](https://github.com/user-attachments/assets/520d92d4-cd35-4870-87b4-4a60bd552a28)

## Procedure:

### Setup the PLC Programming Environment:

Connect the PLC to the computer system and launch the PLC programming software.</br>
Ensure all input and output devices are correctly connected to the PLC’s I/O modules.</br>
Create Ladder Logic Programs:</br>
For each logic gate, create a ladder logic rung that corresponds to the truth table of the gate.</br>
Use normally open (NO) and normally closed (NC) contacts to implement AND, OR, and NOT logic.</br>
For NAND, NOR, and XOR gates, combine the basic gates appropriately in the ladder diagram.</br>
Simulate the Ladder Logic:</br>
Simulate the ladder logic programs in the PLC software.</br>
Toggle the input states and observe the output corresponding to each gate’s truth table.</br>

## Download and Execute:

If available, download the ladder logic program to the PLC and run it.</br>
Verify the outputs by changing the input states using the connected switches and observing the LEDs or output indicators.</br>
Output of Simulation:</br>
For each logic gate, when the inputs are changed according to the truth tables, the corresponding outputs should be observed as follows:</br>
AND Gate: The output LED or indicator should light up only when both inputs are HIGH.</br>
OR Gate: The output should light up when any one or both inputs are HIGH.</br>
NOT Gate: The output should be the inverse of the input state.</br>
NAND Gate: The output should be HIGH except when both inputs are HIGH.</br>
NOR Gate: The output should be HIGH only when both inputs are LOW.</br>
XOR Gate: The output should light up when exactly one input is HIGH.</br>



## SIMULATION RESULTS:

### AND GATE:

![and gate](https://github.com/user-attachments/assets/b9554b06-a7eb-4948-99c5-4ba076008c1d)

### OR GATE:

![image](https://github.com/user-attachments/assets/baaf1dae-6bc8-46be-b49e-05b1f1093021)

### NOT GATE:

![image](https://github.com/user-attachments/assets/4a1ce93d-cc6b-45c6-a550-10b07fe1d7f8)

### NAND GATE:

![Screenshot 2024-08-23 084728](https://github.com/user-attachments/assets/e0717d43-bee3-4211-8372-11cbd742476a)

### NOR GATE:

![image](https://github.com/user-attachments/assets/9022c8fc-0a86-447f-9669-42ba8a48d9ba)

### EX-OR GATE:

![image](https://github.com/user-attachments/assets/235aad23-25d5-4362-9f30-4d70d8a1077f)

## Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
