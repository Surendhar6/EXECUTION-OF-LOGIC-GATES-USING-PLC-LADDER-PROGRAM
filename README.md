# EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM


 # NAME : Surendhhar A
 # REGISTER NUMBER : 212222110049
 # DEPARTMENT : CSE ( IoT )
 # YEAR : III

 
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
### AND Gate:

Function: Outputs HIGH only when all inputs are HIGH.
Ladder Logic: Represented by two or more normally open contacts in series.

### OR Gate:

Function: Outputs HIGH when at least one input is HIGH.
Ladder Logic: Represented by two or more normally open contacts in parallel.

### NOT Gate:

Function: Outputs the inverse of the input signal.
Ladder Logic: Represented by a normally closed contact.

### NAND Gate:

Function: Outputs LOW only when all inputs are HIGH.
Ladder Logic: An AND gate followed by a NOT gate.

### NOR Gate:

Function: Outputs LOW when at least one input is HIGH.
Ladder Logic: An OR gate followed by a NOT gate.

### XOR Gate:

Function: Outputs HIGH when an odd number of inputs are HIGH.
Ladder Logic: Represented by a combination of AND, OR, and NOT gates.
# Truth Tables:

### AND Gate:
![image](https://github.com/user-attachments/assets/31de498b-7938-428f-9298-a11952b6e425)

### OR Gate:
![image](https://github.com/user-attachments/assets/6f109b4b-f379-422d-9295-6b03bf3cf61f)

### NOT Gate:
![image](https://github.com/user-attachments/assets/cdf5822e-9809-4d79-b143-56a08ff77d84)

### NAND Gate:
![image](https://github.com/user-attachments/assets/0a49e6c2-461c-468f-8595-17ac8ecbb018)

### NOR Gate:
![image](https://github.com/user-attachments/assets/55514f51-b886-474a-9856-2dcbc913ced2)

### XOR Gate:
![image](https://github.com/user-attachments/assets/a165326e-39eb-4291-94ad-143a019078c0)

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


# SIMULATION RESULTS :

### AND Gate:
![AND-IIOT](https://github.com/user-attachments/assets/b8c53f51-e9dc-4c28-ae78-ae803614f17f)

### OR Gate:
![OR-IIOT](https://github.com/user-attachments/assets/456925c6-922f-4d24-a5d7-1c985401388c)

### NOT Gate:
![NOT-IIOT](https://github.com/user-attachments/assets/85f57cf9-25c0-4d5d-b0ee-8b032d78f84a)

### NAND Gate:
![NAND-IIOT](https://github.com/user-attachments/assets/36b7ec8e-a3d0-4e35-aafd-dd86f51db448)

### NOR Gate:
![NOR-IIOT](https://github.com/user-attachments/assets/ec2fb2d0-d4c7-44b9-bbbc-11f9a9a78d87)

### XOR Gate:
![EX-OR-IIoT](https://github.com/user-attachments/assets/cf8563a6-0c2d-4efd-bf39-4a218de458a0)

# Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
