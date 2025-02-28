# EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM


 ## NAME : VIGNESH M
 ## REGISTER NUMBER : 212223240176
 ## DEPARTMENT : AIML

 
# Aim:
To implement and verify the functioning of basic logic gates (AND, OR, NOT, NAND, NOR, XOR) using a PLC ladder program and simulate the outputs.

# Apparatus Required:
Programmable Logic Controller (PLC) - A PLC with support for ladder logic programming.
PLC Programming Software - Software like RSLogix, TIA Portal, or CX-Programmer.
Computer System - To run the PLC programming software and perform simulations.
Input Devices - Push buttons or switches to simulate inputs (I/O modules).
Output Devices - LEDs or any indicator to visualize the output of logic gates (I/O modules).
Wires and Connectors - For connecting input/output devices to the PLC.
Power Supply - Appropriate power supply for PLC and peripherals.


# Theory:
Logic gates are the fundamental building blocks of digital circuits, and they process binary inputs to produce a binary output. In PLC programming, these logic gates can be implemented using ladder logic, which is a graphical programming language resembling electrical relay logic.

# Basic Logic Gates:
AND Gate:
Function: Outputs HIGH only when all inputs are HIGH.
Ladder Logic: Represented by two or more normally open contacts in series.


OR Gate:
Function: Outputs HIGH when at least one input is HIGH.
Ladder Logic: Represented by two or more normally open contacts in parallel.


NOT Gate:
Function: Outputs the inverse of the input signal.
Ladder Logic: Represented by a normally closed contact.


NAND Gate:
Function: Outputs LOW only when all inputs are HIGH.
Ladder Logic: An AND gate followed by a NOT gate.


NOR Gate:
Function: Outputs LOW when at least one input is HIGH.
Ladder Logic: An OR gate followed by a NOT gate.


XOR Gate:
Function: Outputs HIGH when an odd number of inputs are HIGH.
Ladder Logic: Represented by a combination of AND, OR, and NOT gates.

# Truth Tables:

AND GATE


![Screenshot 2025-02-27 161955](https://github.com/user-attachments/assets/e93c39af-aa9f-49df-a1a8-c1497eb9b7e7)


OR GATE


![Screenshot 2025-02-27 162003](https://github.com/user-attachments/assets/21b30d36-6a02-4b82-9023-666c427ad354)

NOT GATE


![Screenshot 2025-02-27 162013](https://github.com/user-attachments/assets/238a8d5f-6a02-4690-8b27-5e06ac418c02)

NOR GATE


![Screenshot 2025-02-27 162021](https://github.com/user-attachments/assets/8c99dfd8-8172-4765-b88e-65ef8fdd3f8d)

NAND GATE


![Screenshot 2025-02-27 162027](https://github.com/user-attachments/assets/dd7b9bac-3383-4d2b-98d3-04c3ab96a835)

XOR GATE


![Screenshot 2025-02-27 162035](https://github.com/user-attachments/assets/2be1239d-3f1b-4485-8642-41ca90bf42d7)


# Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer system and launch the PLC programming software.
Ensure all input and output devices are correctly connected to the PLC’s I/O modules.
Create Ladder Logic Programs:

For each logic gate, create a ladder logic rung that corresponds to the truth table of the gate.
Use normally open (NO) and normally closed (NC) contacts to implement AND, OR, and NOT logic.
For NAND, NOR, and XOR gates, combine the basic gates appropriately in the ladder diagram.
Simulate the Ladder Logic:

Simulate the ladder logic programs in the PLC software.
Toggle the input states and observe the output corresponding to each gate’s truth table.
# Download and Execute:

If available, download the ladder logic program to the PLC and run it.
Verify the outputs by changing the input states using the connected switches and observing the LEDs or output indicators.
Output of Simulation:
For each logic gate, when the inputs are changed according to the truth tables, the corresponding outputs should be observed as follows:
AND Gate: The output LED or indicator should light up only when both inputs are HIGH.
OR Gate: The output should light up when any one or both inputs are HIGH.
NOT Gate: The output should be the inverse of the input state.
NAND Gate: The output should be HIGH except when both inputs are HIGH.
NOR Gate: The output should be HIGH only when both inputs are LOW.
XOR Gate: The output should light up when exactly one input is HIGH.


# SIMULATION RESULTS 

AND GATE 


![Screenshot 2025-02-21 153901](https://github.com/user-attachments/assets/aab1c7f1-1544-4604-a5c1-045a05c48dd1)

![Screenshot 2025-02-21 153911](https://github.com/user-attachments/assets/84ad33d9-2c22-48e6-9837-5b28bc4fe865)

![Screenshot 2025-02-21 153923](https://github.com/user-attachments/assets/22eea8d6-266f-4875-b344-096f4b9c5652)

![Screenshot 2025-02-21 153938](https://github.com/user-attachments/assets/b566e9cf-8f28-4468-b090-f683824d0d9d)

OR GATE

![Screenshot 2025-02-21 154257](https://github.com/user-attachments/assets/7e3eb5f8-3de8-40c4-bbcb-ed1242faa7ea)

![Screenshot 2025-02-21 154309](https://github.com/user-attachments/assets/12472aa6-9745-4c21-a987-fe267202ac15)

![Screenshot 2025-02-21 154320](https://github.com/user-attachments/assets/d6213bcb-6c69-4384-9327-a661c9e70370)

![Screenshot 2025-02-21 154328](https://github.com/user-attachments/assets/dd797580-7867-48c6-8cd8-837c0f89aed9)

NOT GATE

![Screenshot 2025-02-28 063359](https://github.com/user-attachments/assets/8ea729cc-0753-4bd1-8c34-3e68121158e4)

![Screenshot 2025-02-28 063413](https://github.com/user-attachments/assets/7526e3bb-178f-42aa-9080-9fd64d41f718)

NOR GATE

![Screenshot 2025-02-28 082035](https://github.com/user-attachments/assets/e7d4a68f-cd8b-4c9d-b227-28e7293925cc)

![Screenshot 2025-02-28 082054](https://github.com/user-attachments/assets/8135f548-d5cd-4bf8-917b-1758c269eb84)

![Screenshot 2025-02-28 082105](https://github.com/user-attachments/assets/471afc08-7a65-4423-9505-abc983306906)

![Screenshot 2025-02-28 082154](https://github.com/user-attachments/assets/f0a63cd6-b9a7-4604-b69b-8b33a97d0d4d)



NAND GATE

![Screenshot 2025-02-21 160029](https://github.com/user-attachments/assets/5876c8d6-36df-44e1-9db8-0c271075285a)

![Screenshot 2025-02-21 160109](https://github.com/user-attachments/assets/8a9827e5-5c6c-4509-af48-e044f1e3c14d)

![Screenshot 2025-02-21 160134](https://github.com/user-attachments/assets/af7d4396-08a2-4f0b-858c-d3f29aeb47e7)

![Screenshot 2025-02-21 160147](https://github.com/user-attachments/assets/00bbfcb0-3ede-4667-b8e6-0ab5d4e764eb)


XOR GATE
![Screenshot 2025-02-28 091030](https://github.com/user-attachments/assets/a7cbdfe8-6cac-4c4b-bf95-fd8048df475c)

![Screenshot 2025-02-28 091050](https://github.com/user-attachments/assets/de73df54-29c5-43bd-94a6-3e7271b3d400)

![Screenshot 2025-02-28 091121](https://github.com/user-attachments/assets/f6543ae6-34fe-4e19-82ed-e1d201b792af)

#Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
