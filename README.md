# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

FULLADDER:
<img width="1024" height="1536" alt="fu;;adder" src="https://github.com/user-attachments/assets/2e04e10c-18d7-44de-8258-9382cb910a5d" />

FULLSUBTRACTOR:

<img width="1024" height="1536" alt="full subtractor" src="https://github.com/user-attachments/assets/44097ec1-82b3-4dbe-8b8d-23c87d29d22c" />


**Procedure**

1.Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram.

**Program to design a full adder and full subtractor circuit and verify its truth table in quartus using Verilog programming:**

<img width="1920" height="1080" alt="program 4" src="https://github.com/user-attachments/assets/2a2016ee-39c1-4304-b0ad-e6b36fe68d48" />

Developed by: RegisterNumber:25015904 

**RTL Schematic**

<img width="1920" height="1080" alt="rtl 4" src="https://github.com/user-attachments/assets/40f6af63-ea99-43b0-895d-4aaaa9441090" />

**Output Timing Waveform**

<img width="1920" height="1080" alt="waveform 4" src="https://github.com/user-attachments/assets/52790d9d-2bfa-4481-99bb-6d7d15f6d9f0" />

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



