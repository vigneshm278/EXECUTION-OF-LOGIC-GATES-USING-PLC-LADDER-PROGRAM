#### NAME : VIGNESH M
#### REG.NO : 212223240176
#### DEP: AIML

# Experiment -1 
# EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM


 
### Aim:
To implement and verify the functioning of basic logic gates (AND, OR, NOT, NAND, NOR, XOR) using a PLC ladder program and simulate the outputs.

### Apparatus Required:	
Programmable Logic Controller (PLC) - A PLC with support for ladder logic programming.
PLC Programming Software - Software like RSLogix, TIA Portal, or CX-Programmer.
Computer System - To run the PLC programming software and perform simulations.
Input Devices - Push buttons or switches to simulate inputs (I/O modules).
Output Devices - LEDs or any indicator to visualize the output of logic gates (I/O modules).
Wires and Connectors - For connecting input/output devices to the PLC.
Power Supply - Appropriate power supply for PLC and peripherals.


### Theory:
Logic gates are the fundamental building blocks of digital circuits, and they process binary inputs to produce a binary output. In PLC programming, these logic gates can be implemented using ladder logic, which is a graphical programming language resembling electrical relay logic.

### Basic Logic Gates:
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

### Truth Tables:

**AND Gate:**

| Input A | Input B | Output |
|---------|---------|--------|
|   0     |   0     |   0    |
|   0     |   1     |   0    |
|   1     |   0     |   0    |
|   1     |   1     |   1    |

**OR Gate:**

| Input A | Input B | Output |
|---------|---------|--------|
|   0     |   0     |   0    |
|   0     |   1     |   1    |
|   1     |   0     |   1    |
|   1     |   1     |   1    |

**NOT Gate:**

| Input | Output |
|-------|--------|
|   0   |   1    |
|   1   |   0    |

**NAND Gate:**

| Input A | Input B | Output |
|---------|---------|--------|
|   0     |   0     |   1    |
|   0     |   1     |   1    |
|   1     |   0     |   1    |
|   1     |   1     |   0    |

**NOR Gate:**

| Input A | Input B | Output |
|---------|---------|--------|
|   0     |   0     |   1    |
|   0     |   1     |   0    |
|   1     |   0     |   0    |
|   1     |   1     |   0    |

**XOR Gate:**

| Input A | Input B | Output |
|---------|---------|--------|
|   0     |   0     |   0    |
|   0     |   1     |   1    |
|   1     |   0     |   1    |
|   1     |   1     |   0    |

 
### Procedure

**1. Setup the PLC Programming Environment:**
   - Connect the PLC to the computer system and launch the PLC programming software.
   - Ensure all input and output devices are correctly connected to the PLC’s I/O modules.

**2. Create Ladder Logic Programs:**
   - For each logic gate, create a ladder logic rung that corresponds to the truth table of the gate.
   - Use normally open (NO) and normally closed (NC) contacts to implement AND, OR, and NOT logic.
   - For NAND, NOR, and XOR gates, combine the basic gates appropriately in the ladder diagram.

**3. Simulate the Ladder Logic:**
   - Simulate the ladder logic programs in the PLC software.
   - Toggle the input states and observe the output corresponding to each gate’s truth table.

Here’s the section with proper formatting:

**4. Download and Execute:**

- If available, download the ladder logic program to the PLC and run it.
- Verify the outputs by changing the input states using the connected switches and observing the LEDs or output indicators.

### Output of Simulation:
- **AND Gate:** The output LED or indicator should light up only when both inputs are HIGH.
- **OR Gate:** The output should light up when any one or both inputs are HIGH.
- **NOT Gate:** The output should be the inverse of the input state.
- **NAND Gate:** The output should be HIGH except when both inputs are HIGH.
- **NOR Gate:** The output should be HIGH only when both inputs are LOW.
- **XOR Gate:** The output should light up when exactly one input is HIGH.


### SIMULATION RESULTS 

![Screenshot 2024-08-23 084625](https://github.com/user-attachments/assets/d5b6636c-fe10-4c77-9ce8-9d4733dfdd26)

![Screenshot 2024-08-23 084420](https://github.com/user-attachments/assets/9a6f4f2f-688a-4505-9ff1-8120f1d516ff)

![Screenshot 2024-08-23 084247](https://github.com/user-attachments/assets/12b93b2b-aa27-4ef5-aca5-1fbc9afb6589)

![Screenshot 2024-08-23 084052](https://github.com/user-attachments/assets/58df9a50-65a2-4625-ada9-b3be0c76314b)

![Screenshot 2024-08-23 083641](https://github.com/user-attachments/assets/caeff490-c6ea-4a2c-bcb4-4174f8acfceb)



### Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
