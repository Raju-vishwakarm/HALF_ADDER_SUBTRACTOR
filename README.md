EXP3=HALF ADDER AND HALF SUBSTRACTOR 

NAME=H.VEDHANTH

REF NO=24003775

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

![WhatsApp Image 2024-12-18 at 22 31 10_de817ddd](https://github.com/user-attachments/assets/4c28ebf1-9e32-4de1-a163-0687ec3395a7)



**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
![WhatsApp Image 2024-12-18 at 22 03 47_d989393d](https://github.com/user-attachments/assets/07034ef4-13d8-4805-9327-cbd6a4e2f3f1)

![WhatsApp Image 2024-12-18 at 22 04 49_9b5d2e31](https://github.com/user-attachments/assets/6b728f23-6869-4d1a-9cc1-eed74a57c1f4)

**Output/TIMING Waveform**

1.HALF ADDER

![WhatsApp Image 2024-12-18 at 22 20 40_8377b2a7](https://github.com/user-attachments/assets/39f9c7af-bf15-4fd2-aa95-cad0259fbe63)


2.HALF SUBSTRACTOR

![WhatsApp Image 2024-12-18 at 22 20 55_6698c1c8](https://github.com/user-attachments/assets/d0c51bed-98a0-4699-acb1-262a8cb036d1)


Result:THUS THE HALF ADDER AND HALF SUBSTRACTOR CIRCUITS ARE DESIGNED AND TRUTH TABLE IS VERIFIED USING QUARTUS SPOFTWARW
