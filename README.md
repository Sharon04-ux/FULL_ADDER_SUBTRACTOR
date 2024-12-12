### NAME : SHARON ARUL BHARATHI J.F
### REF NO. : 24005394
# EXP NO.4 : FULL ADDER SUBTRACTOR


## AIM:

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

## EQUIPMENTS REQUIRED:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

## FULL ADDER AND FULL SUBTRACTOR

## FULL ADDER:

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

## Figure -1 FULL ADDER


## FULL SUBTRACTOR :

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

## TRUTHTABLE :
![WhatsApp Image 2024-11-28 at 13 54 29](https://github.com/user-attachments/assets/ca73c884-9076-4a4e-af82-eb0d70d16801)


## PROCEDURE :

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.

## PROGRAM:
![WhatsApp Image 2024-11-28 at 14 28 20](https://github.com/user-attachments/assets/1a287887-089e-4151-ac4b-29cf022ef7d5)

## RTL SCHEMATIC :
![WhatsApp Image 2024-11-28 at 14 28 19](https://github.com/user-attachments/assets/af9d50b1-3ada-4ee2-a442-9ff94ba9266b)

## OUTPUT/TIMING WAVEFORM
![WhatsApp Image 2024-11-28 at 14 28 20 (1)](https://github.com/user-attachments/assets/27c7b976-74de-48fa-a9f5-a696ef88b84b)


## RESULT:
Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.
